<template>
	<div class="md:py-8">
		<div class="px-4 sm:px-0 md:max-w-2xl lg:max-w-4xl xl:max-w-6xl mx-auto">
			<div class="flex flex-wrap lg:flex-nowrap lg:-mx-4">
				<div class="w-full mt-8 overflow-hidden md:mt-0 md:w-1/2">
					<div class="flex items-center h-full text-left">
						<div class="max-w-lg py-12">
							<h2 class="text-lg sm:text-2xl md:text-3xl lg:text-4xl text-blue-1000 dark:text-white font-semibold pr-4" style="line-height: 50px;">Dryva mobile <br class="hidden md:inline-block"> application.</h2>
							<p class="mt-2 md:mt-10 text-blue-600 dark:text-white text-base sm:text-lg lg:text-xl lg:pr-6" style="line-height: 34px;">
								Dryva is a professional hiring service that connects trusted drivers
								to clients who already own vehicles but require drivers.</p>
							<div class="mt-10">
								<div class="mt-10">
									<router-link
                                        class="uppercase yellowbutton mt-8"
											:to="{ name: 'dryva' }">
										CASE STUDY
									</router-link>
								</div>
							</div>
						</div>
					</div>
				</div>
				<div class="w-full md:w-1/2 pt-12 lg:pt-32">
                    <img class="h-auto" src="../assets/images/dryva.png" alt="dryva">
				</div>
			</div>
		</div>
	</div>
</template>

<script>
	export default {
		name: "Dryva"
	}
</script>

<style scoped>

</style>
