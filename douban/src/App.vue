<template>
  <div id="app">
    <router-view/>
   	<breads></breads>
 
  </div>
</template>

<script>
	
	import breads from './components/HelloWorld'
	
	export default {
	  name: 'App',
	 
	  components:{
	  	breads
	  }
	}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
