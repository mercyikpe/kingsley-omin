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
							<h1 class="text-4xl md:text-5xl lg:text-9xl text-blue-700 dark:text-white font-semibold leading-none mx-auto lg:ml-0">
								Hi there,<br/>nice to <br/> meet you.
							</h1>
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

			<!-- Works counter-->
			<section class="py-24 px-4 bg-white dark:bg-black">
				<WorkCount />
			</section>

			<section id="about-paragraph" class="bg-white dark:bg-black py-4">
				<div class="container mx-auto px-4 text-blue-600 dark:text-white text-base md:text-xl">
					<p class="my-6 md:my-8">
						Hello, I’m Kingsley Omin a Product Designer passionate about solving problems using the user-centred design approach to
						simplifying the solution that also accommodates new users. I’m currently based in Lagos, Nigeria. My design process usually
						involves design thinking which starts by empathising with the users and understanding the problem, then research and analyze
						to gain more insights, prototype and test to see if the solution works, then further analysis again to achieve a better product
						that is usable and memorable.
					</p>
					<p class="my-6 md:my-8">I work across user research, UX design, UI design, prototyping and product testing because
						I believe that great design isn't just about creating something that looks good, It's about creating simple and delightful
						products that are accessible and easy to use. I’m constantly captivated by the possibilities that design and technology
						can bring, so I stay motivated to create impact across the world with my designs. With design being so versatile,
						I'm passionate about improving and helping others grow in the field and also cultivating meaningful relationships.
						I am always hungry to learn more about human-centred design because I have a passion for creating beautiful and delightful
						experiences.
					</p>
					<p class="my-6 md:my-8">When I’m not designing, I enjoy playing video games (soccer), watch my favourite team Barcelona play or lifting weight
						at the gym to keep fit . I love blue because it signifies calmness and white is also beautiful. I’m excited to help you turn
						your ideas into something usable.
					</p>

					<div class="flex flex-wrap justify-between items-center w-full lg:w-2/5">
						<address class="flex justify-start items-center">
							<a href="tel:+2347033218457" class="flex items-center px-1 no-underline">
								<Icon
										name="call-color"
										class="cursor-pointer hover:opacity-75 text-yellow-600"
										title="Call me"
								/> <span class="ml-2 text-base font-semibold">+234 703 321 8457</span>
							</a>
						</address>
						<address class="flex justify-start items-center mt-2">
							<a href="mailto:kingsleyomin23@gmail.com" class="flex items-center px-1 no-underline">
								<Icon
										name="email-color"
										class="cursor-pointer hover:opacity-75 text-yellow-600"
										title="Send me a mail"
								/> <span class="-mt-2 ml-2 text-base font-semibold">kingsleyomin23@gmail.com</span>
							</a>
						</address>
					</div>

					<div class="my-12">
						<a href="#" class="text-white uppercase sm:font-xl uppercase py-3 px-6 sm:py-3 sm:px-8 rounded shadow-lg bg-yellow-600 mt-8 font-medium mx-auto lg:ml-0">
							My Resume
						</a>
					</div>
				</div>
			</section>


			<!-- Make something great-->
			<section class="bg-white dark:bg-black px-4 py-20 md:py-40">
				<div class="container mx-auto bg-purple-200 text-blue-600 rounded-lg">
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
				</div>
			</section>

		</div>

		<footer class="bg-white dark:bg-black">
			<Footer />
		</footer>
	</div>

</template>
<script>
	import Header from "../components/Header";
	import Footer from "../components/Footer";
	import WorkCount from "../components/WorkCount";
	import Icon from "../assets/icons/Icon";
	import DarkModeToggle from "../components/DarkModeToggle";

	export default {
		name: "About",
		components: {DarkModeToggle, Icon, WorkCount, Header, Footer}
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
