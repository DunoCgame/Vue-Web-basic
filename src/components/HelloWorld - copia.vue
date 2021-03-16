<template>
 <div class="hello">
		<h1>{{ msg }}</h1>
		<p>{{per}}</p>
		<div>
		  <b-button>Button</b-button>
		  <b-button variant="danger">Button</b-button>
		  <b-button variant="success">Button</b-button>
		  <b-button variant="outline-primary">Button</b-button>
		</div>
		<div>
			<b-form-group label-cols="4" label-cols-lg="2" label-size="sm" label="Small" label-for="input-sm">
			<b-form-input id="input-sm" size="sm"></b-form-input>
			</b-form-group>

			<b-form-group label-cols="4" label-cols-lg="2" label="Default" label-for="input-default">
			<b-form-input id="input-default"></Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.b-form-input>
			</b-form-group>

			<b-form-group label-cols="4" label-cols-lg="2" label-size="lg" label="Large" label-for="input-lg">
			<b-form-input id="input-lg" size="lg"></b-form-input>
			</b-form-group>
		</div>
		
		<b-container class="bv-example-row">
		<b-row>
			<b-col>
				<h2>hila</h2>
				<p>{{per}}</p>			
			</b-col>
			<b-col>
				<h2>hila</h2>
				<p>{{per}}</p>
			</b-col>
		</b-row>

		<b-row>
			<b-col>
			Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
			</b-col>
			<b-col>
			Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
			</b-col>
		</b-row>
				<b-row>
			<b-col>
				<h2>hila</h2>
				<p>{{per}}</p>			
			</b-col>
		</b-row>
		</b-container>
</div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data(){
	return{

		per:
			"Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum."
			
		}
	
	},
  props:{
    msg: String,
  }
}//cierre defaut
</script>
