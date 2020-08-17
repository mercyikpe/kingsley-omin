<template>
	<div class="my-8">
		<div class="container mx-auto px-6">
			<div class="flex flex-wrap lg:flex-nowrap lg:-mx-4">
				<div class="w-full mt-8 overflow-hidden md:mt-0 md:w-1/2">
					<div class="flex items-center h-full text-left">
						<div class="max-w-md py-12">
							<h2 class="text-2xl lg:text-4xl text-blue-800 dark:text-white font-semibold leading-none pr-4">Dryva mobile application.</h2>
							<p class="mt-10 text-blue-600 dark:text-white pr-10 text-base md:text-xl">
								Dryva is a professional hiring service that connects trusted drivers
								to clients who already own vehicles but require drivers.</p>
							<div class="mt-10">
								<div class="mt-10">
									<router-link
											class="text-white sm:font-xl uppercase py-3 px-6 sm:py-3 sm:px-8 rounded shadow-lg bg-yellow-600 mt-8 font-medium"
											:to="{ name: 'dryva' }">
										CASE STUDY
									</router-link>
								</div>
							</div>
						</div>
					</div>
				</div>
				<div class="w-full md:w-1/2 pt-12 lg:pt-32">
					<img class="" src="https://res.cloudinary.com/mercyikpe/image/upload/v1596748572/kingsley%20omin/dryva.png" alt="dryva">
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
