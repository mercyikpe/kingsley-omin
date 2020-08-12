<template>
	<div class="min-h-screen flex flex-col font-sans">
		<div class="flex-grow">
			<AboutHero />

			<section class="my-24 px-4">
				<WorkCount />
			</section>

			<section id="about-paragraph" class="container mx-auto text-blue-600 text-base md:text-xl px-4">
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
									class="cursor-pointer hover:opacity-75"
									title="Logo"
									width="30"
							/> <span class=" ml-2 text-base font-semibold">+234 703 321 8457</span>
						</a>
					</address>
					<address class="flex justify-start items-center mt-2">
						<a href="mailto:kingsleyomin23@gmail.com" class="flex items-center px-1 no-underline">
							<Icon
									name="email-color"
									class="cursor-pointer hover:opacity-75"
									title="Logo"
									width="30"
							/> <span class="-mt-2 ml-2 text-base font-semibold">kingsleyomin23@gmail.com</span>
						</a>
					</address>
				</div>

				<div class="my-12">
					<a href="#" class="text-white uppercase sm:font-xl uppercase py-3 px-6 sm:py-3 sm:px-8 rounded shadow-lg bg-yellow-600 mt-8 font-medium mx-auto lg:ml-0">
						My Resume
					</a>
				</div>
			</section>

			<section class="px-4 my-20 md:my-40">
				<div class="container mx-auto bg-purple-200 text-blue-600 rounded-lg">
					<div class="max-w-full py-16 lg:py-24 px-4 lg:px-8 flex relative">
						<Icon
								name="quote-sm"
								class="cursor-pointer hover:opacity-75 lg:hidden pt-2 pl-6"
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

		<Footer />
	</div>
</template>
<script>
	import Footer from "../components/Footer";
	import AboutHero from "../components/AboutHero";
	import WorkCount from "../components/WorkCount";
	import Icon from "../assets/icons/Icon";

	export default {
		name: "About",
		components: { Icon, WorkCount, AboutHero, Footer}
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
