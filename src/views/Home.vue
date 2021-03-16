<template>
  <div class="home">
		<Jumbotron/>
		<Posts/>		
		<Sidebar/>
		<Footer/>
  </div>
</template>

<script>
// @ is an alias to /src

import Footer from '@/components/Footer.vue';
import Sidebar from '@/components/Sidebar.vue';
import Jumbotron from '@/components/Jumbotron.vue';
import Posts from '@/components/Posts.vue';


export default {
  name:'home',
	  components:{
			 Jumbotron, Posts, Sidebar, Footer
	  }
}
</script>
