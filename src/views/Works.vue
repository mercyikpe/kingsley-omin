<template>
	<div class="min-h-screen flex flex-col font-sans">
		<div class="flex-grow">

			<WorksHero />

			<MyProjects />

			<section class="bg-purple-100">
				<SavologyProfile />
			</section>

			<section class="pb-8 lg:pb-24">
				<Dryva />
			</section>

		</div>

		<Footer />
	</div>
</template>
<script>
	import Footer from "../components/Footer";
	import WorksHero from "../components/WorksHero";
	import MyProjects from "../components/MyProjects";
	import SavologyProfile from "../components/Savology-profile";
	import Dryva from "../components/Dryva";

	export default {
		name: "Works",
		components: {Dryva, SavologyProfile, MyProjects, WorksHero, Footer}
	}
</script>

<style scoped>
	address {
		font-weight: 400;
		font-size: 16px;
		line-height: 20px;
		letter-spacing: -0.08px;
		font-style: normal;
	}
</style>
