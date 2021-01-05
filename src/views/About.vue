<template>
	<div class="min-h-screen flex flex-col font-sans">
		<div class="flex-grow">
			<main class="bg-white dark:bg-black relative font-Graphik">
                <div class="z-40 lg:pt-6">
                    <!-- Nav Bar-->
                    <Header />
                    <!-- Nav Bar-->
                </div>

                <section class="py-6">
                    <div class="px-4 sm:px-0 md:max-w-2xl lg:max-w-4xl xl:max-w-6xl mx-auto flex flex-col md:flex-row lg:justify-between items-center relative">
                        <div class="w-full xl:w-3/6 flex flex-col items-start text-center lg:text-left">
                            <h1 class="text-4xl md:text-5xl lg:text-9xl text-blue-700 dark:text-white font-bold leading-none mx-auto lg:ml-0">Hi there,<br/>nice to <br/> meet you.</h1>
                        </div>

                        <div class="items-center flex justify-center md:justify-end sm:w-4/6 pt-12">
                            <img class="h-auto sm:w-4/5" style="width: 477px; height: 497px" src="https://res.cloudinary.com/mercyikpe/image/upload/v1597306363/kingsley%20omin/KingsleyOmin.png" alt="Kingsley Omin">
                        </div>
                    </div>
                </section>

			</main>

			<!-- Works counter-->
			<section class="pt-12 lg:pt-24 pb-8 lg:pb-12 px-4 bg-white dark:bg-black">
				<WorkCount />
			</section>

			<section id="about-paragraph" class="bg-white dark:bg-black py-4">
				<div class="px-4 sm:px-0 md:max-w-2xl lg:max-w-4xl xl:max-w-6xl mx-auto text-blue-600 dark:text-white text-base md:text-xl">
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
                        <router-link
                            class="uppercase yellowbutton mt-8"
                            :to="{ name: 'contact' }">
                            My Resume
                        </router-link>
					</div>
				</div>
			</section>


			<!-- Make something great-->
            <section class="bg-white dark:bg-black pt-12 lg:pt-24 pb-8 lg:pb-24 ">
                <div class="px-4 sm:px-0 md:max-w-2xl lg:max-w-4xl xl:max-w-6xl mx-auto bg-purple-200 text-blue-600 rounded-lg">
                    <div class="max-w-full py-16 lg:py-24 px-8 lg:px-20 flex relative">
                        <div class="text-left w-full ml-8">
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

	export default {
		name: "About",
		components: {Icon, WorkCount, Header, Footer}
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
    p {
        line-height: 44px;
    }
</style>
