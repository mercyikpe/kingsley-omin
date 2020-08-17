<template>
	<div class="py-8">
		<div class="container mx-auto lg:px-24">
			<div class="flex flex-wrap md:flex-no-wrap lg:-mx-4">
				<div class="w-full md:w-1/2 pt-12 lg:pt-32 px-8 lg:px-0 order-last lg:order-first">
					<img class="" src="https://res.cloudinary.com/mercyikpe/image/upload/v1596748576/kingsley%20omin/random-design.png" alt="random design">
				</div>

				<div class="w-full mt-8 md:mx-4 overflow-hidden md:mt-0 md:w-1/2">
					<div class="flex items-center h-full text-left">
						<div class="px-10 max-w-lg py-12">
							<h2 class="text-2xl lg:text-4xl text-blue-800 dark:text-white font-semibold leading-none">Some of my random designs</h2>
							<p class="mt-10 text-blue-600 dark:text-white text-base lg:text-xl">
								So when I'm not working on a real-life project or reading design-related books
								and articles, I keep myself busy by creating beautiful design mock-ups.
							</p>
							<div class="mt-10">
								<router-link
										class="text-white sm:font-xl uppercase py-3 px-6 sm:py-3 sm:px-8 rounded shadow-lg bg-yellow-600 mt-8 font-medium"
										:to="{ name: 'contact' }">
									GET IN TOUCH
								</router-link>
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
		name: "Random-Design"
	}
</script>

<style scoped>

</style>
