<template>
	<div/>
</template>

<script>
import '@google/model-viewer';

export default {
	name: 'HelloWorld',

	created() {
		const model = document.createElement('model-viewer');
		model.src = '@/assets/freshhat2.gltf';
		document.body.appendChild(model);
	},
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
