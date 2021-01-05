<template>
	<div class="">
		<div class="px-4 md:max-w-2xl lg:max-w-4xl xl:max-w-6xl mx-auto">
			<div class="flex flex-wrap lg:flex-no-wrap lg:-mx-4">
				<div class="w-full md:w-1/2 pt-6 md:pt-12 lg:pt-32 order-last lg:order-first">
					<img class="" src="../assets/images/savology.png" alt="savology">
				</div>

				<div class="w-full md:mt-8 lg:mx-4 overflow-hidden md:mt-0 md:w-1/2 order-first">
					<div class="flex items-center h-full text-left">
						<div class="lg:pl-20 max-w-full lg:max-w-xl py-12">
							<h2 class="text-lg sm:text-2xl md:text-3xl lg:text-4xl text-blue-1000 font-semibold" style="line-height: 50px;">Savology mobile <br class="hidden md:inline-block">application.</h2>
							<p class="mt-2 md:mt-10 text-blue-600 text-base sm:text-lg lg:text-xl" style="line-height: 34px;">Savology is a mobile application that enables parents and guardians to save money specifically for their children’s university education.</p>
							<div class="mt-10">
								<router-link
										class="uppercase yellowbutton mt-8"
										:to="{ name: 'savology' }">
									CASE STUDY
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
		name: "Savology-profile"
	}
</script>

<style scoped>

</style>
