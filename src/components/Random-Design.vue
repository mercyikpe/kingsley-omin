<template>
	<div class="py-8">
		<div class="px-4 md:px-8 lg:px-12 md:max-w-2xl lg:max-w-4xl xl:max-w-6xl mx-auto">
			<div class="flex flex-wrap lg:flex-no-wrap lg:-mx-4">
				<div class="w-full lg:w-1/2 pt-12 lg:pt-32 px-4 lg:px-0 order-last lg:order-first">
					<img class="" src="../assets/images/random-design.png" alt="random design">
				</div>

				<div class="w-full mt-8 md:mx-4 overflow-hidden md:mt-0 lg:w-1/2">
					<div class="flex items-center h-full text-left">
						<div class="lg:pl-12 max-w-xl py-12">
							<h2 class="text-lg sm:text-2xl md:text-3xl lg:text-4xl text-blue-1000 dark:text-white font-semibold" style="line-height: 50px;">Some of my random <br class="hidden md:inline-block">designs</h2>
							<p class="mt-2 md:mt-10 text-blue-600 dark:text-white text-base sm:text-lg lg:text-xl" style="line-height: 32px;">
								So when I'm not working on a real-life project or reading design-related books
								and articles, I keep myself busy by creating beautiful design <span style="white-space: nowrap">mock-ups</span>.
							</p>
							<div class="mt-10 hidden">
								<router-link
                                    class="uppercase yellowbutton mt-8"
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
