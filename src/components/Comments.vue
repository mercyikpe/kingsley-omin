<template>
	<div class="mt-32">
		<div class="max-w-6xl mx-auto py-24 px-8">
			<h3 class="text-4xl font-semibold text-center text-blue-700">Comment from teammates</h3>

			<div class="comments">
				<div class="grid grid-cols-1 md:grid-cols-2">


					<div class="max-w-xl m-4">
						<div class="flex flex-col min-h-full">
							<div class="px-12 pt-10 flex-grow">
								<p class="text-blue-800 opacity-75 text-sm font-medium italic text-left tracking-wide comment-single">
									Kingsley is a clear communicator, problem-solver and a critical thinker that delivers
									exceptional quality of work in time. It is always a pleasure to work with and we look forward
									to working with him again.
								</p>
								<div class="pt-6 text-left">
									<h5 class="text-blue-800 font-semibold text-sm">Mercy Ikpe</h5>
									<h6 class="text-blue-800  text-xs mt-1">Frontend Developer</h6>
								</div>
							</div>
						</div>
					</div>
					<div class="max-w-xl m-4">
						<div class="flex flex-col min-h-full">
							<div class="px-12 pt-10 flex-grow">
								<p class="text-blue-800 opacity-75 text-sm font-medium italic text-left tracking-wide comment-single">
									Kingsley is an excellent team player with a keen eye for designing user centric products.
									He understands and sees the larger picture of what the prduct should look, feel and achieve.
									His abilities to translate the clients idea to workable product is unmatched. He is a dependable team player too.
								</p>
							</div>
							<div class="px-12 pt-6 text-left">
								<h5 class="text-blue-800 font-semibold text-sm">Celestine Omin</h5>
								<h6 class="text-blue-800  text-xs mt-1">CEO, Alta Labs</h6>
							</div>
						</div>
					</div>

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
</style>
