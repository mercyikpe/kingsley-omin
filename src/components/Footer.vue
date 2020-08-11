<template>
	<div class="pb-8 container mx-auto">
		<hr style="background: #1F3564;" />
		<div class="pt-6 text-blue-600">
			<div class="flex flex-wrap lg:justify-between items-center m-auto">
				<div class="flex flex-col lg:flex-row mx-auto lg:mx-0">
					<img class="h-10 w-16 self-center" src="https://res.cloudinary.com/mercyikpe/image/upload/v1596667405/kingsley%20omin/favicon.png" alt="logo" />

					<ul class="flex flex-row items-center mb-8 lg:mb-0 lg:ml-24">
						<li class="border-t md:border-none px-4 lg:px-0">
							<a href="/" class="sm:px-4 py-2 block md:inline-block mx-4 no-underline text-blue-600 hover:text-blue-700">
								Portfolio
							</a>
						</li>

						<li class="border-t md:border-none px-4 lg:px-0">
							<a href="/" class="sm:px-4 py-2 block md:inline-block mx-4 no-underline text-blue-600 hover:text-blue-700">
								Work
							</a>
						</li>

						<li class="border-t md:border-none px-4 lg:px-0">
							<a href="/" class="sm:px-4 py-2 block md:inline-block mx-4 no-underline text-blue-600 hover:text-blue-700">
								Contact
							</a>
						</li>
					</ul>
				</div>

				<div class="w-full sm:block lg:w-1/4 mt-2 md:text-left" id="contact">
					<address class="flex justify-center items-center md:justify-start">
						<a href="tel:+2347033218457" class="block md:inline-block px-1 no-underline">
							<Icon
									name="call"
									class="fa-2x cursor-pointer hover:opacity-75"
									title="Logo"
									width="30"
							/> +234 703 321 8457
						</a>
					</address>
					<address class=" flex justify-center md:justify-start mt-2">
						<a href="mailto:kingsleyomin23@gmail.com" class="block md:inline-block px-1 no-underline">
							<Icon
									name="email"
									class="fa-2x cursor-pointer hover:opacity-75"
									title="Logo"
									width="30"
							/> kingsleyomin23@gmail.com
						</a>
					</address>
				</div>

			</div>
		</div>

		<div class="">
			<div class="flex pb-5 m-auto pt-5 flex-wrap lg:justify-between items-center">
				<div class="w-full lg:w-3/4 mt-2 text-center lg:text-left order-last lg:order-first">
					<p class="text-sm md:text-base mt-4 lg:pt-0 text-blue-600">
						© 2020 Kingsley Omin. All Rights Reserved.
					</p>
				</div>
				<div class="w-full lg:w-1/4">
					<div class="md:flex-auto mt-6 lg:mt-2 flex-row flex justify-center lg:justify-start">

						<ul class="menu border-b md:border-none flex justify-end list-reset m-0 w-full md:w-auto">
							<li class="border-t md:border-none">
								<a href="/" class="block md:inline-block px-2 no-underline">
									<Icon
											name="dribble"
											class="fa-2x cursor-pointer hover:opacity-75"
											title="Logo"
											width="30"
									/>
								</a>
							</li>

							<li class="border-t md:border-none">
								<a href="/" class="block md:inline-block px-2 no-underline">
									<Icon
											name="linked-in"
											class="fa-2x cursor-pointer hover:opacity-75"
											title="Logo"
											width="30"
									/>
								</a>
							</li>

							<li class="border-t md:border-none">
								<a href="/" class="block md:inline-block px-2 no-underline">
									<Icon
											name="twitter"
											class="fa-2x cursor-pointer hover:opacity-75"
											title="Logo"
											width="30"
									/>
								</a>
							</li>

							<li class="border-t md:border-none">
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
