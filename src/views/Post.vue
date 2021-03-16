<template>
	<div class="posts_info">
		<b-container class="bv-example-row">
							
					<h2>{{posts.title}}</h2>
					<p>{{posts.body}}</p>
					 
					 
					
					<button @click="back">back home</button>
		
			
					
		</b-container>
	</div>
	
</template>

<script>
export default{
    name:"Posts",
   data() {
    return {
		posts:[]
		
		
    };
	
  },
    methods: {
		ver:function(){ console.log("press");},
		back:function(){ this.$router.push("/"); }
      
    },
  async created(){
		const response = await fetch("https://jsonplaceholder.typicode.com/posts/"+this.$route.params.id);
			  const data = await response.json();
			   this.posts = data;
			   
				
		
  }
  
  
	
}
</script>
<!--$route.params.id-->