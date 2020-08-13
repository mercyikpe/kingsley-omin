<template>
	<div class="min-h-screen flex flex-col font-sans">
		<div class="flex-grow pb-8">
			<main class="bg-white relative font-Graphik">
				<div class="container mx-auto px-4 lg:px-0 relative z-40 lg:pt-6 relative">
					<Header />
				</div>

				<section class="py-6">
					<div class="container px-4 lg:px-0 mx-auto flex flex-col md:flex-row lg:justify-between items-center relative">
						<div class="w-full xl:w-3/6 flex flex-col items-start py-8 text-center lg:text-left">
							<h1 class="text-9xl text-blue-700 font-semibold leading-none hidden lg:flex">Say hello 👋</h1>
							<h1 class="text-4xl text-blue-700 font-semibold leading-none lg:hidden mx-auto mb-6">Say hello 👋</h1>

							<div class="mt-12 xl:mt-32 mx-2 md:mx-0">
								<div class="flex items-center text-left">
									<p class="w-1/2 text-base md:text-xl text-blue-700">Shoot me an email</p>
									<a href="mailto:kingsleyomin23@gmail.com" class="w-1/2 text-base md:text-xl underline text-yellow-600">
										kingsleyomin23@gmail.com
									</a>
								</div>
								<div class="flex items-center mt-10 text-left">
									<p class="w-1/2 text-base md:text-xl text-blue-700">Contact me </p>
									<a href="tel:+2347033218457" class="w-1/2 text-base md:text-xl no-underline text-yellow-600">
										+234 703 321 8457
									</a>
								</div>
							</div>
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
		</div>

		<Footer />
	</div>
</template>

<script>
	import Header from "../components/Header";
	import Footer from "../components/Footer";
	import Icon from "../assets/icons/Icon";
	export default {
		name: "Contact",
		components: {Icon, Header, Footer}
	}
</script>

<style scoped>

</style>
