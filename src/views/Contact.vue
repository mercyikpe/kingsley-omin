<template>
	<div class="min-h-screen flex flex-col font-sans contact-page bg-white dark:bg-black">
		<div class="flex-grow pb-8">

			<main class="relative">
                <div class="z-40 lg:pt-6">
                    <!-- Nav Bar-->
                    <Header />
                    <!-- Nav Bar-->
                </div>

                <section class="py-6">
                    <div class="px-4 sm:px-0 md:max-w-2xl lg:max-w-4xl xl:max-w-6xl mx-auto flex flex-col md:flex-row lg:justify-between items-center relative">
                        <div class="w-full xl:w-3/6 flex flex-col items-start py-8 text-center lg:text-left">
                            <h1 class="text-4xl md:text-5xl lg:text-9xl text-blue-700 dark:text-white font-semibold leading-none mx-auto mb-6 md:mb-0 md:ml-0">Say hello 👋</h1>

                            <div class="mt-12 xl:mt-32 mx-2 md:mx-0">
                                <div class="flex items-center text-left">
                                    <p class="w-1/2 text-base md:text-xl text-blue-700 dark:text-white">Shoot me an email</p>
                                    <a href="mailto:kingsleyomin23@gmail.com" class="w-1/2 text-base md:text-xl underline text-yellow-600">
                                        kingsleyomin23@gmail.com
                                    </a>
                                </div>
                                <div class="flex items-center mt-10 text-left">
                                    <p class="w-1/2 text-base md:text-xl text-blue-700 dark:text-white">Contact me </p>
                                    <a href="tel:+2347033218457" class="w-1/2 text-base md:text-xl no-underline text-yellow-600">
                                        +234 703 321 8457
                                    </a>
                                </div>
                            </div>
                        </div>

                        <div class="items-center flex justify-center md:justify-end sm:w-4/6 pt-12">
                            <img class="h-auto sm:w-4/5" style="width: 477px; height: 497px" src="https://res.cloudinary.com/mercyikpe/image/upload/v1597306363/kingsley%20omin/KingsleyOmin.png" alt="Kingsley Omin">
                        </div>
                    </div>
                </section>

			</main>
		</div>

        <footer class="bg-white dark:bg-black">
            <Footer />
        </footer>
	</div>
</template>

<script>
	import Header from "../components/Header";
	import Footer from "../components/Footer";

	export default {
		name: "Contact",
		components: {Header, Footer}
	}
</script>

<style scoped>
</style>
