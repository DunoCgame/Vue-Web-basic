<template>
		 <div class="area-buttons" style="background:white; display:flex; justify-content:center; padding:10px; margin:2px;">
				<router-link :to="{name:'Foto', params:{id:item}}" 
				v-for="(item,index) of fotoArreglo" :key="index">
					<b-button-group style="margin:20px;">
								<b-button>{{item}}</b-button>	
					</b-button-group>
				</router-link>
		</div>
</template>

<script>


export default {
  name:'Foto',
  data(){
	return{
			fotoArreglo:[1,2,3]
			}
	},
}//cierre defaut
</script>
