<template>
	<div class="posts_info">
		<b-container class="bv-example-row" fluid>
 
				<div v-for="post, index in posts"  :key="post.id" v-if="index < 3">				
					<h2>{{post.title}}</h2>
					<p>{{post.body}}</p>				 
					
						<router-link :to="{name:'Post', params:{id:post.id}}">
						<br>
								<b-button block variant="primary">ver</b-button>				
						</router-link>
				</div>
					
		</b-container>
	</div>
</template>

<script>
export default{
    name:"Posts",
   data() {
    return {
		posts:[],
		
	children: [
	  {
		path: "/user/:username/info",
		name: "Info",
		props: true,
		  }
		]
    };
	
  },
    methods: {
		ver:function(){ console.log("press");}
      
    },

  async created(){
		const response = await fetch("https://jsonplaceholder.typicode.com/posts");
			  const data = await response.json();
			   this.posts = data;
			   
				
		
  }
  
  
	
}
</script>