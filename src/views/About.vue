<template>
	  <div class="about">		
			<Jumbotron/>
			<HelloWorld/>			
			<Foto/>			
			<Sidebar/>
			<Footer/> 
	  </div>
</template>


<script>
import Footer from '@/components/Footer.vue';
import Sidebar from '@/components/Sidebar.vue';
import Jumbotron from '@/components/Jumbotron.vue';
import Posts from '@/components/Posts.vue';
import Foto from '@/components/fotografia.vue';
import HelloWorld from '@/components/ContentAbout.vue';

export default {
  name:'about',
  components: {
    Posts, Jumbotron, HelloWorld, Sidebar, Footer, Foto
  }
}
</script>

<style>




</style>