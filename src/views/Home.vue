<template>
	<div class="home">

		<main class="bg-white dark:bg-black relative font-Graphik">
			<div class="container mx-auto px-4 lg:px-0 relative z-40 lg:pt-6 relative">

				<!-- Nav Bar-->
				<Header />
				<!-- Nav Bar-->
			</div>
			<section class="py-6">
				<div class="container px-4 lg:px-0 mx-auto flex flex-col md:flex-row lg:justify-between items-center relative">
					<div class="w-full xl:w-3/6 flex flex-col items-start py-8 text-center lg:text-left">
						<h1 class="text-4xl md:text-5xl lg:text-9xl text-blue-700 dark:text-white font-bold leading-none mx-auto lg:ml-0">Kingsley <br class="hidden md:flex"/> Omin</h1>
						<h2 class="text-xl xl:text-2xl text-yellow-600 font-medium leading-none mt-4 mb-2 lg:mb-6 tracking-tight mx-auto lg:ml-0">A Product Designer</h2>
						<p class="tracking-normal text-blue-800 dark:text-white font-medium px-5 lg:px-0">A user experience designer with a deep understanding of the principle of (UX), and versed in designing for different platforms.</p>

						<a href="#" class="text-white sm:font-xl uppercase py-3 px-6 sm:py-3 sm:px-8 rounded shadow-lg bg-yellow-600 mt-8 font-medium mx-auto lg:ml-0">GET IN TOUCH</a>
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

		<section class="bg-white  dark:bg-black">
			<RandomDesign />
		</section>

		<!-- Make something great-->
		<section class="bg-white dark:bg-black px-4 py-12 lg:py-32">
			<div class="container mx-auto bg-yellow-700 text-white rounded-lg">
				<div class="max-w-full py-16 lg:py-24 px-4 lg:px-8 flex relative">
					<Icon
							name="quote-sm"
							class="absolute cursor-pointer hover:opacity-75 lg:hidden pt-2"
							title="Logo"
							width="20"
					/>
					<Icon
							name="quote"
							class="mt-4 cursor-pointer hover:opacity-75 hidden lg:flex relative"
							title="Logo"
							width="60"
					/>
					<div class="text-left w-full ml-8">
						<h2 class="text-4xl lg:text-7xl font-semibold text-left tracking-wide leading-tight">Let’s make <br> something Great <br>Together</h2>

						<a href="mailto:kingsleyomin23@gmail.com" class="mt-8 block md:inline-block text-base lg:text-2xl font-medium no-underline">
							<span class="mr-1 lg:mr-3">Email:</span> kingsleyomin23@gmail.com
						</a>
					</div>
				</div>
			</div>
		</section>

		<section class="bg-white dark:bg-black">
			<Comments />
		</section>

		<footer class="bg-white dark:bg-black">
			<Footer />
		</footer>
	</div>
</template>

<script>
	import MyProjects from "../components/MyProjects";
	import SavologyProfile from "../components/Savology-profile";
	import Dryva from "../components/Dryva";
	import RandomDesign from "../components/Random-Design";
	import Comments from "../components/Comments";
	import Footer from "../components/Footer";
	import Header from "../components/Header";
	import Icon from "../assets/icons/Icon";
	import DarkModeToggle from "../components/DarkModeToggle";

	export default {
		name: 'Home',
		components: {
			DarkModeToggle,
			Icon,
			Footer,
			Comments,
			RandomDesign,
			Dryva,
			SavologyProfile,
			MyProjects,
			Header
		}
	}
</script>
