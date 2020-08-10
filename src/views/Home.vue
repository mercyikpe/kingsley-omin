<template>
	<div class="home">
		<Hero />
		<!--    <img alt="Vue logo" src="../assets/logo.png">-->
	</div>
</template>

<script>
	// @ is an alias to /src
	// import HelloWorld from '@/components/HelloWorld.vue'

	import Hero from "../components/Hero";
	export default {
		name: 'Home',
		components: {
			Hero
			// HelloWorld
		}
	}
</script>
