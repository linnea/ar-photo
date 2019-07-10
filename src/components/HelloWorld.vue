<template>
  <div class="hello">
    <model-viewer alt="A 3D model of an astronaut." src="@/assets/freshhat2.gltf" ar/>
  </div>
</template>

<script>
import '@google/model-viewer';

export default {
	name: 'HelloWorld',
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
