<template>
	<main class="bg-white relative font-Graphik">
		<div class="container mx-auto px-4 lg:px-0 relative z-40 pt-6 relative">
			<NavBar/>
		</div>
		<section class="relative py-6">
			<div class="container mx-auto flex flex-col sm:flex-row items-center relative">
				<div class="sm:w-1/2 xl:w-3/6 flex flex-col items-start py-24 sm:py-0 text-left">
					<h1 class="text-6xl xl:text-9xl text-blue-700 font-bold leading-none">Kingsley <br/> Omin</h1>
					<h2 class="text-xl xl:text-2xl text-yellow-600 font-medium leading-none mt-4 mb-6 tracking-tight">A Product Designer</h2>
					<p class="tracking-normal text-blue-800 font-medium">A user experience designer with a deep understanding of the principle of (UX), and versed in designing for different platforms.</p>
					<a href="#" class="text-white sm:font-xl uppercase py-3 px-6 sm:py-3 sm:px-8 rounded shadow-lg bg-yellow-600 mt-8 font-medium">GET IN TOUCH</a>
				</div>
				<div class="hidden sm:flex items-center justify-center xl:justify-end w-1/2 xl:w-4/6 py-20">
					<img class="h-full w-4/5" src="https://res.cloudinary.com/mercyikpe/image/upload/v1596703082/kingsley%20omin/ko.png" alt="Kingsley Omin">
				</div>
			</div>
			<div class="absolute right-0 top-0 mt-24 pt-3 mr-12">
				<Icon
						name="light-switch"
						class="cursor-pointer hover:opacity-75 pb-8"
						title="switch"
						width="30"
				/>
				<p class="transform -rotate-90 mt-4 font-medium text-blue-800 -ml-8">Switch View</p>
			</div>
		</section>

	</main>
</template>

<script>
	import Icon from "../assets/icons/Icon";
	import NavBar from "./NavBar";
	export default {
		name: "Hero",
		components: {NavBar, Icon}
	}
</script>

<style scoped>

</style>
