<template>
	<div class="about">
					<Jumbotron/>
			<FotoData/>
			<InfoAbout/>
			<Sidebar/>
			<Footer/>
	</div>
</template>

<script>
import Jumbotron from '@/components/Jumbotron.vue';
import InfoAbout from '@/components/ContentAbout.vue';
import FotoData from '@/components/Fotosdata.vue';
import Footer from '@/components/Footer.vue';
import Sidebar from '@/components/Sidebar.vue';

export default{
	name:"fotos",
		components:{
					 Jumbotron, FotoData, InfoAbout ,Sidebar, Footer
			  }

}



</script>




