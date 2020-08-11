<template>
	<div class="home">
		<Hero />

		<MyProjects />

		<section class="bg-purple-100">
			<SavologyProfile />
		</section>

		<section class="bg-white">
			<Dryva />
		</section>

		<section class="bg-white">
			<RandomDesign />
		</section>

		<section>
			<MakeSomethingGreat />
		</section>

		<section class="bg-white">
			<Comments />
		</section>

		<!--    <img alt="Vue logo" src="../assets/logo.png">-->
	</div>
</template>

<script>
	// @ is an alias to /src
	// import HelloWorld from '@/components/HelloWorld.vue'

	import Hero from "../components/Hero";
		import MyProjects from "../components/MyProjects";
		import SavologyProfile from "../components/Savology-profile";
		import Dryva from "../components/Dryva";
		import RandomDesign from "../components/Random-Design";
		import MakeSomethingGreat from "../components/MakeSomethingGreat";
		import Comments from "../components/Comments";
	export default {
		name: 'Home',
		components: {
					Comments,
					MakeSomethingGreat,
					RandomDesign,
					Dryva,
					SavologyProfile,
					MyProjects,
			Hero
			// HelloWorld
		}
	}
</script>
