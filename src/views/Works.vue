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
                            <h1 class="text-4xl md:text-5xl lg:text-9xl text-blue-700 dark:text-white font-bold leading-none mx-auto lg:ml-0">
                                Some of <br/>my work.
                            </h1>
                        </div>

                        <div class="items-center flex justify-center md:justify-end sm:w-4/6 pt-12">
                            <img class="h-auto sm:w-4/5" style="width: 477px; height: 497px" src="https://res.cloudinary.com/mercyikpe/image/upload/v1597306363/kingsley%20omin/KingsleyOmin.png" alt="Kingsley Omin">
                        </div>
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

		</div>

		<footer class="bg-white dark:bg-black">
			<Footer />
		</footer>
	</div>
</template>
<script>
	import Header from "../components/Header";
	import Footer from "../components/Footer";
	import MyProjects from "../components/MyProjects";
	import SavologyProfile from "../components/Savology-profile";
	import Dryva from "../components/Dryva";

	export default {
		name: "Works",
		components: {Dryva, SavologyProfile, MyProjects,  Footer, Header}
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
