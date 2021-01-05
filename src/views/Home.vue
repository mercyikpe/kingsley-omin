<template>
    <div class="home">
        <main class="bg-white dark:bg-black relative font-Graphik">
            <div class="z-40 lg:pt-6">

                <!-- Nav Bar-->
                <Header />
                <!-- Nav Bar-->
            </div>

            <section class="py-6">
                <div class="px-4 sm:px-0 md:max-w-2xl lg:max-w-4xl xl:max-w-6xl mx-auto flex flex-col md:flex-row lg:justify-between items-center relative">
                    <div class="w-full xl:w-3/6 flex flex-col items-start text-center lg:text-left">
                        <h1 class="text-4xl md:text-5xl lg:text-9xl text-blue-700 dark:text-white font-bold leading-none mx-auto lg:ml-0">Kingsley <br class="hidden md:flex"/> Omin</h1>
                        <h2 class="text-xl xl:text-2xl text-yellow-600 font-medium leading-none mt-4 mb-2 lg:mb-6 tracking-tight mx-auto lg:ml-0">A Product Designer</h2>
                        <p class="tracking-normal text-blue-800 dark:text-white font-medium px-5 lg:px-0">A user experience designer versed in adaptable design for different platforms, with a committment to user friendliness.</p>

                        <a href="#" class="text-white sm:font-xl uppercase py-3 px-8 sm:py-3 sm:px-10 bg-yellow-600 mt-10 font-medium mx-auto lg:ml-0" style="border-radius: 6px;">GET IN TOUCH</a>
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

        <section class="bg-white dark:bg-black">
            <RandomDesign />
        </section>

        <!-- Make something great-->
        <section class="bg-white dark:bg-black py-12 lg:py-32">
            <div class="px-4 sm:px-0 md:max-w-2xl lg:max-w-4xl xl:max-w-6xl mx-auto bg-yellow-700 text-white rounded-lg">
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

export default {
    name: 'Home',
    components: {
        Footer,
        Comments,
        RandomDesign,
        Dryva,
        SavologyProfile,
        MyProjects,
        Header,
    }
}
</script>

