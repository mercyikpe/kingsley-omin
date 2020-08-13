<template>
	<main class="bg-white relative font-Graphik">
		<div class="container mx-auto px-4 lg:px-0 relative z-40 lg:pt-6 relative">
			<Header />
		</div>

		<section class="py-6">
			<div class="container px-4 lg:px-0 mx-auto flex flex-col md:flex-row lg:justify-between items-center relative">
				<div class="w-full xl:w-3/6 flex flex-col items-start py-8 text-center lg:text-left">
					<h1 class="text-4xl md:text-5xl lg:text-9xl text-blue-700 font-semibold leading-none hidden lg:flex">Some of
						<br/>my work.</h1>
				</div>

				<div class="items-center flex justify-center md:justify-end w-full xl:w-4/6 lg:py-20">
					<!--					<img class="h-full lg:w-4/5" src="https://res.cloudinary.com/mercyikpe/image/upload/v1596703082/kingsley%20omin/ko.png" alt="Kingsley Omin">-->
					<img class="h-auto lg:w-4/5" src="../assets/images/KingsleyOmin.png" alt="Kingsley Omin">
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
		name: "WorksHero",
		components: {Icon, Header}
	}
</script>

<style scoped>

</style>
