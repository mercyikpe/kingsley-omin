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

		<section class="container mx-auto my-32  bg-yellow-700 text-white rounded-lg">
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
				<div class="text-left w-full ml-4 lg:ml-6">
					<h2 class="text-4xl lg:text-7xl font-semibold text-left tracking-wide leading-tight">Let’s make <br> something Great <br>Together</h2>

					<a href="mailto:kingsleyomin23@gmail.com" class="mt-8 block md:inline-block text-base lg:text-2xl font-medium no-underline">
						<span class="mr-1 lg:mr-3">Email:</span> kingsleyomin23@gmail.com
					</a>
				</div>
			</div>

			<MakeSomethingGreat class="hidden" />
		</section>

		<section class="bg-white">
			<Comments />
		</section>

		<Footer />
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
	import Footer from "../components/Footer";
	import Icon from "../assets/icons/Icon";

	export default {
		name: 'Home',
		components: {
			Icon,
			Footer,
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
