<template>
	<div class="mt-32">
		<div class="max-w-6xl mx-auto py-8 lg:py-24 px-8">
			<h3 class="text-2xl lg:text-4xl font-semibold text-center text-blue-700">Comment from teammates</h3>

			<div class="comments">
				<div class="grid grid-cols-1 md:grid-cols-2 hidden md:flex">
					<div class="max-w-xl m-4">
						<div class="flex flex-col min-h-full">
							<div class="lg:px-12 pt-10 flex-grow">
								<p class="text-blue-800 opacity-75 text-sm font-medium italic text-center lg:text-left tracking-wide comment-single">
									Kingsley is a clear communicator, problem-solver and a critical thinker that delivers
									exceptional quality of work in time. It is always a pleasure to work with and we look forward
									to working with him again.
								</p>
								<div class="pt-6 text-center lg: text-left">
									<h5 class="text-blue-800 font-semibold text-sm">Mercy Ikpe</h5>
									<h6 class="text-blue-800  text-xs mt-1">Frontend Developer</h6>
								</div>
							</div>
						</div>
					</div>
					<div class="max-w-xl m-4">
						<div class="flex flex-col min-h-full">
							<div class="lg:px-12 pt-10 flex-grow">
								<p class="text-blue-800 opacity-75 text-sm font-medium italic text-center lg:text-left tracking-wide comment-single">
									Kingsley is an excellent team player with a keen eye for designing user centric products.
									He understands and sees the larger picture of what the prduct should look, feel and achieve.
									His abilities to translate the clients idea to workable product is unmatched. He is a dependable team player too.
								</p>
							</div>
							<div class="px-12 pt-6 text-center lg:text-left">
								<h5 class="text-blue-800 font-semibold text-sm">Celestine Omin</h5>
								<h6 class="text-blue-800  text-xs mt-1">CEO, Alta Labs</h6>
							</div>
						</div>
					</div>

				</div>
			</div>

			<div class="carousel relative mt-6 lg:hidden">
				<div class="carousel-inner relative overflow-hidden w-full">
					<!--Slide 1-->
					<input class="carousel-open" type="radio" id="carousel-1" name="carousel" aria-hidden="true" hidden="" checked="checked">
					<div class="carousel-item absolute opacity-0" style="height:30vh;">
						<div class="block h-full w-full text-center">
							<p class="text-blue-800 opacity-75 text-sm font-medium italic text-center lg:text-left tracking-wide comment-single">
								Kingsley is a clear communicator, problem-solver and a critical thinker that delivers
								exceptional quality of work in time. It is always a pleasure to work with and we look forward
								to working with him again.
							</p>
							<div class="pt-6 text-center lg: text-left">
								<h5 class="text-blue-800 font-semibold text-sm">Mercy Ikpe</h5>
								<h6 class="text-blue-800  text-xs mt-1">Frontend Developer</h6>
							</div>
						</div>
					</div>

					<!--Slide 2-->
					<input class="carousel-open" type="radio" id="carousel-2" name="carousel" aria-hidden="true" hidden="">
					<div class="carousel-item absolute opacity-0" style="height:30vh;">
						<div class="block h-full w-full text-white text-5xl text-center">
							<p class="text-blue-800 opacity-75 text-sm font-medium italic text-center lg:text-left tracking-wide comment-single">
								Kingsley is an excellent team player with a keen eye for designing user centric products.
								He understands and sees the larger picture of what the prduct should look, feel and achieve.
								His abilities to translate the clients idea to workable product is unmatched. He is a dependable team player too.
							</p>
							<div class="pt-6 text-center lg: text-left">
								<h5 class="text-blue-800 font-semibold text-sm">Celestine Omin</h5>
								<h6 class="text-blue-800  text-xs mt-1">CEO, Alta Labs</h6>
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
	export default {
		name: "Comments"
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
	/*#carousel-1:checked ~ .control-1,*/
	/*#carousel-2:checked ~ .control-2,*/
	/*#carousel-3:checked ~ .control-3 {*/
	/*	display: block;*/
	/*}*/
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
	/*#carousel-1:checked ~ .control-1 ~ .carousel-indicators li:nth-child(1) .carousel-bullet,*/
	/*#carousel-2:checked ~ .control-2 ~ .carousel-indicators li:nth-child(2) .carousel-bullet,*/
	/*#carousel-3:checked ~ .control-3 ~ .carousel-indicators li:nth-child(3) .carousel-bullet {*/
	/*	color: #2b6cb0;  !*Set to match the Tailwind colour you want the active one to be *!*/
	/*}*/
</style>
