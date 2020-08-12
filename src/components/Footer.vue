<template>
	<div class="pb-10 container mx-auto px-4 lg:px-0">
		<hr style="background: #1F3564; opacity: 0.33; height: 2px;" />
		<div class="pt-6 text-blue-600">

			<div class="flex flex-wrap md:justify-between md:flex-no-wrap items-center m-auto">
				<div class="flex flex-row items-center mx-auto mx-0 w-full pt-6">

					<img class="h-10 w-16 self-center" src="https://res.cloudinary.com/mercyikpe/image/upload/v1596667405/kingsley%20omin/favicon.png" alt="logo" />

					<ul class="flex flex-row justify-between md:justify-start items-center lg:mb-0 ml-12 md:ml-16 lg:ml-24 w-full">
						<li class="">
							<router-link
									class="py-2 block md:inline-block mx-4 no-underline text-blue-600 hover:text-blue-700"
									:to="{ name: 'works' }"
									active-class="text-yellow-600"
									exact>
								Works
							</router-link>
						</li>

						<li class="">
							<router-link
									class="py-2 block md:inline-block mx-4 no-underline text-blue-600 hover:text-blue-700"
									:to="{ name: 'about' }"
									active-class="text-yellow-600"
									exact>
								About Me
							</router-link>
						</li>

						<li class="">
							<router-link
									class="py-2 block md:inline-block mx-4 no-underline text-blue-600 hover:text-blue-700"
									:to="{ name: 'contact' }"
									active-class="text-yellow-600"
									exact>
								Contact
							</router-link>
						</li>
					</ul>
				</div>

				<div class="w-full sm:block lg:w-1/3 mt-6 md:mt-2 md:text-left pt-8 md:pt-0" id="contact">
					<address class="flex justify-start items-center">
						<a href="tel:+2347033218457" class="flex items-center px-1 no-underline">
							<Icon
									name="call"
									class="fa-2x cursor-pointer hover:opacity-75"
									title="Logo"
									width="30"
							/> <span class="-mt-2">+234 703 321 8457</span>
						</a>
					</address>
					<address class=" flex justify-start items-center mt-2">
						<a href="mailto:kingsleyomin23@gmail.com" class="flex items-center px-1 no-underline">
							<Icon
									name="email"
									class="fa-2x cursor-pointer hover:opacity-75"
									title="Logo"
									width="30"
							/> <span class="-mt-2">kingsleyomin23@gmail.com</span>
						</a>
					</address>
				</div>

			</div>
		</div>

		<div class="">
			<div class="flex pb-5 m-auto pt-5 flex-wrap lg:justify-between items-center">

				<div class="w-full lg:w-3/4 mt-2 text-center lg:text-left order-last lg:order-first">
					<p class="text-base mt-4 lg:pt-0 text-blue-600">
						© 2020 Kingsley Omin. All Rights Reserved.
					</p>
				</div>

				<div class="w-full lg:w-1/4 pb-6 md:pb-0">
					<div class="md:flex-auto mt-2 flex-row flex justify-center lg:justify-start">

						<ul class="flex justify-start md:justify-end list-reset m-0 w-full md:w-auto">
							<li>
								<a href="/" class="block md:inline-block pr-2 no-underline">
									<Icon
											name="dribble"
											class="fa-2x cursor-pointer hover:opacity-75"
											title="Logo"
											width="30"
									/>
								</a>
							</li>

							<li>
								<a href="/" class="block md:inline-block px-2 no-underline">
									<Icon
											name="linked-in"
											class="fa-2x cursor-pointer hover:opacity-75"
											title="Logo"
											width="30"
									/>
								</a>
							</li>

							<li>
								<a href="/" class="block md:inline-block px-2 no-underline">
									<Icon
											name="twitter"
											class="fa-2x cursor-pointer hover:opacity-75"
											title="Logo"
											width="30"
									/>
								</a>
							</li>

							<li class="">
								<a href="/" class="block md:inline-block pl-2 no-underline">
									<Icon
											name="medium"
											class="fa-2x cursor-pointer hover:opacity-75"
											title="Logo"
											width="30"
									/>
								</a>
							</li>
						</ul>
					</div>
				</div>
			</div>
		</div>
	</div>
</template>

<script>
	import Icon from "../assets/icons/Icon";

	export default {
		name: "Footer",
		components: {
			Icon
		}
	};
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
