<template>
	<main class="bg-white relative font-Graphik">
		<div class="container mx-auto px-4 lg:px-0 relative z-40 lg:pt-6 relative">
			<Header />
		</div>
		<section class="py-6">
			<div class="container px-4 lg:px-0 mx-auto flex flex-col md:flex-row lg:justify-between items-center relative">
				<div class="w-full xl:w-3/6 flex flex-col items-start py-8 text-center lg:text-left">
					<h1 class="text-9xl text-blue-700 font-bold leading-none hidden lg:flex">Kingsley <br/> Omin</h1>
					<h1 class="text-4xl text-blue-700 font-bold leading-none lg:hidden mx-auto mb-6">Kingsley Omin</h1>
					<h2 class="text-xl xl:text-2xl text-yellow-600 font-medium leading-none mt-4 mb-2 lg:mb-6 tracking-tight mx-auto lg:ml-0">A Product Designer</h2>
					<p class="tracking-normal text-blue-800 font-medium px-5 lg:px-0">A user experience designer with a deep understanding of the principle of (UX), and versed in designing for different platforms.</p>

					<a href="#" class="text-white sm:font-xl uppercase py-3 px-6 sm:py-3 sm:px-8 rounded shadow-lg bg-yellow-600 mt-8 font-medium mx-auto lg:ml-0">GET IN TOUCH</a>
				</div>

				<div class="items-center flex justify-center md:justify-end w-full xl:w-4/6 lg:py-20">
					<img class="h-auto lg:w-4/5" src="https://res.cloudinary.com/mercyikpe/image/upload/v1597306363/kingsley%20omin/KingsleyOmin.png" alt="Kingsley Omin">
				</div>
			</div>
			<div class="absolute right-0 top-0 mt-24 pt-24 mr-12 hidden lg:block">
				<Icon
						name="light-switch"
						class="cursor-pointer hover:opacity-75 pb-8 pt-2"
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
	import Header from "./Header";

	export default {
		name: "Hero",
		components: {Icon, Header}
	}
</script>

<style scoped>

</style>
