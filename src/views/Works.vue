<template>
	<div class="min-h-screen flex flex-col font-sans">
		<div class="flex-grow">

			<main class="bg-white dark:bg-black relative font-Graphik">
				<div class="container mx-auto px-4 lg:px-0 relative z-40 lg:pt-6 relative">

					<!-- Nav Bar-->
					<Header />
					<!-- Nav Bar-->
				</div>
				<section class="py-6">
					<div class="container px-4 lg:px-0 mx-auto flex flex-col md:flex-row lg:justify-between items-center relative">
						<div class="w-full xl:w-3/6 flex flex-col items-start py-8 text-center lg:text-left">
							<h1 class="text-4xl md:text-5xl lg:text-9xl text-blue-700 dark:text-white font-semibold leading-none mx-auto lg:ml-0">Some of
								<br/>my work.</h1>
						</div>

						<div class="items-center flex justify-center md:justify-end w-full xl:w-4/6 lg:py-20">
							<img class="h-auto lg:w-4/5" src="https://res.cloudinary.com/mercyikpe/image/upload/v1597306363/kingsley%20omin/KingsleyOmin.png" alt="Kingsley Omin">
						</div>
					</div>
					<div class="absolute right-0 top-0 mt-24 pt-24 mr-12 hidden lg:block">
						<DarkModeToggle />
						<p class="transform -rotate-90 mt-4 font-medium text-blue-800 dark:text-white -ml-8" @click="alert">Switch View</p>
					</div>
				</section>

			</main>

			<MyProjects />

			<section class="bg-purple-100">
				<SavologyProfile />
			</section>

			<section class="bg-white dark:bg-black">
				<Dryva />
			</section>
<!--			<section class="pb-8 lg:pb-24">-->
<!--				<Dryva />-->
<!--			</section>-->

		</div>

		<footer class="bg-white dark:bg-black">
			<Footer />
		</footer>
	</div>
</template>
<script>
	import Header from "../components/Header";
	import Footer from "../components/Footer";
	import MyProjects from "../components/MyProjects";
	import SavologyProfile from "../components/Savology-profile";
	import Dryva from "../components/Dryva";
		import DarkModeToggle from "../components/DarkModeToggle";

	export default {
		name: "Works",
		components: {DarkModeToggle, Dryva, SavologyProfile, MyProjects,  Footer, Header}
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
