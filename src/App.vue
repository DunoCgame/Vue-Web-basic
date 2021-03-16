<template>
	  <div id="app">  
	
	  	<b-navbar type="dark" variant="dark">
			    <b-navbar-nav>
				
					<b-navbar-brand href="#">
					  <img src="@/assets/logo.png" alt="Kitten" width="30px" heigth="30px">
					</b-navbar-brand>
				 
					<b-navbar variant="faded" type="light">
						<b-navbar-brand href="#">BootstrapVue</b-navbar-brand>
					</b-navbar>
		
				</b-navbar-nav>
	
	
					<b-navbar-nav class="ml-auto">
					  <b-nav-item :to="{name:'Home'}" exact>Home</b-nav-item>
					  <b-nav-item :to="{name:'About'}" >About</b-nav-item>
					</b-navbar-nav>

		 </b-navbar>
		  <div>
			<router-view/>
		  </div>
	  </div> 
</template>


