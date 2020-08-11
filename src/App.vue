<template>
	<div id="app">
		<!--      <router-link to="/">Home</router-link> |-->
		<!--      <router-link to="/about">About</router-link>-->
		<router-view/>
		<Footer class="hidden lg:block" />
	</div>
</template>

<style>
	#app {
		font-family: Graphik, sans-serif;
		-webkit-font-smoothing: antialiased;
		-moz-osx-font-smoothing: grayscale;
	}

	/*#nav a.router-link-exact-active {*/
	/*  color: #42b983;*/
	/*}*/
</style>

<script>
	import Footer from "./components/Footer";
	export default {
		components: {
			Footer

		}
	}
</script>
