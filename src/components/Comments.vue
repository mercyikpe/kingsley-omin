<template>
	<div class="">
		<div class="px-4 sm:px-0 md:max-w-2xl lg:max-w-4xl xl:max-w-6xl mx-auto py-8 lg:py-24 px-4 sm:px-6 md:px-8">
			<h3 class="text-2xl lg:text-4xl font-semibold text-center text-blue-700 dark:text-white">Comments from teammates</h3>
            <Icon
                name="quote-sm"
                class="absolute lg:hidden pt-4"
                title="Logo"
                width="20"
            />
            <Icon
                name="quote"
                class="mt-4 hidden lg:flex relative"
                title="Logo"
                width="60"
            />
			<div class="comments text-blue-800 dark:text-white">
				<div class="grid grid-cols-1 lg:grid-cols-2 hidden lg:flex">
					<div class="max-w-xl m-4">
						<div class="flex flex-col min-h-full">
							<div class="lg:px-12 pt-4 flex-grow">
								<p class="opacity-75 text-sm font-medium italic text-center lg:text-left tracking-wide comment-single">
									Kingsley is a clear communicator, problem-solver and a critical thinker that delivers
									exceptional quality of work in time. It is always a pleasure to work with and we look forward
									to working with him again.
								</p>
								<div class="pt-6 text-center lg:text-left text-blue-800 dark:text-white">
									<h5 class="font-semibold text-sm">Mercy Ikpe</h5>
									<h6 class="text-xs mt-1">Frontend Developer</h6>
								</div>
							</div>
						</div>
					</div>
					<div class="max-w-xl m-4">
						<div class="flex flex-col min-h-full">
							<div class="lg:px-12 pt-4 flex-grow">
								<p class="opacity-75 text-sm font-medium italic text-center lg:text-left tracking-wide comment-single">
									Kingsley is an excellent team player with a keen eye for designing user centric products.
									He understands and sees the larger picture of what the prduct should look, feel and achieve.
									His abilities to translate the clients idea to workable product is unmatched. He is a dependable team player too.
								</p>
							</div>
							<div class="px-12 pt-6 text-center lg:text-left">
								<h5 class="font-semibold text-sm">Celestine Omin</h5>
								<h6 class="text-xs mt-1">CEO, Alta Labs</h6>
							</div>
						</div>
					</div>

				</div>
			</div>

			<div class="carousel relative mt-8 text-blue-800 dark:text-white lg:hidden">
				<div class="carousel-inner relative overflow-hidden w-full">
					<!--Slide 1-->
					<input class="carousel-open" type="radio" id="carousel-1" name="carousel" aria-hidden="true" hidden="" checked="checked">
					<div class="carousel-item absolute opacity-0 h-smallScreen xs:h-small sm:h-56 md:h-64">
						<div class="block h-full w-full text-center">
							<p class="opacity-75 text-sm font-medium italic text-center lg:text-left tracking-wide comment-single">
								Kingsley is a clear communicator, problem-solver and a critical thinker that delivers
								exceptional quality of work in time. It is always a pleasure to work with and we look forward
								to working with him again.
							</p>
							<div class="pt-6 text-center lg: text-left">
								<h5 class="font-semibold text-sm">Mercy Ikpe</h5>
								<h6 class="text-xs mt-1">Frontend Developer</h6>
							</div>
						</div>
					</div>

					<!--Slide 2-->
					<input class="carousel-open" type="radio" id="carousel-2" name="carousel" aria-hidden="true" hidden="">
					<div class="carousel-item absolute opacity-0 h-smallScreen xs:h-small sm:h-56 md:h-64">
						<div class="block h-full w-full text-5xl text-center">
							<p class="opacity-75 text-sm font-medium italic text-center lg:text-left tracking-wide comment-single">
								Kingsley is an excellent team player with a keen eye for designing user centric products.
								He understands and sees the larger picture of what the prduct should look, feel and achieve.
								His abilities to translate the clients idea to workable product is unmatched. He is a dependable team player too.
							</p>
							<div class="pt-6 text-center lg: text-left">
								<h5 class="font-semibold text-sm">Celestine Omin</h5>
								<h6 class="text-xs mt-1">CEO, Alta Labs</h6>
							</div>
						</div>
					</div>

					<!-- Add indicators for each slide-->
					<ol class="carousel-indicators">
						<li class="inline-block mr-3">
							<label for="carousel-1" class="carousel-bullet cursor-pointer block text-4xl text-gray-600 hover:text-blue-700">•</label>
						</li>
						<li class="inline-block mr-3">
							<label for="carousel-2" class="carousel-bullet cursor-pointer block text-4xl text-gray-400 hover:text-blue-700">•</label>
						</li>
					</ol>

				</div>
			</div>

		</div>
	</div>
</template>

<script>
	import Icon from "@/assets/icons/Icon";
    export default {
		name: "Comments",
        components: {Icon}
    }
</script>

<style scoped>
	.comments {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
	}
	.comment-single {
		line-height: 26px;
	}
	.carousel-open:checked + .carousel-item {
		position: static;
		opacity: 100;
	}
	.carousel-item {
		-webkit-transition: opacity 0.6s ease-out;
		transition: opacity 0.6s ease-out;
	}
	.carousel-indicators {
		list-style: none;
		margin: 0;
		padding: 0;
		position: absolute;
		bottom: 2%;
		left: 0;
		right: 0;
		text-align: center;
		z-index: 10;
	}

    /* Extra small devices (phones, 600px and down) */

    /*@media only screen and (max-width: 440px) {*/
    /*    .carousel-item-height {*/
    /*        height: 75vh;*/
    /*        max-height: 75vh;*/
    /*    }*/
    /*}*/
    /*@media only screen and (max-width: 640px) {*/
    /*    .carousel-item-height {*/
    /*        height: 40vh !important;*/
    /*        max-height: 40vh !important;*/
    /*    }*/
    /*}*/
    /*@media only screen and (max-width: 1023px) {*/
    /*    .carousel-item-height {*/
    /*        height: 25vh;*/
    /*        max-height: 25vh;*/
    /*    }*/
    /*}*/
</style>
