<template>
  <img alt="CV - My Photo" src="./assets/avatar.jpg">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@300;600&display=swap');
#app {
	font-family: 'Montserrat', sans-serif;
	font-weight: 300;
	background-color: #999;
	text-align: center;
	color: #2e2e2e;
	margin-top: 60px;
}
img  {
	max-width: 30%;
	height: auto;
}
</style>
