<template>
	<div class="pb-10 container mx-auto px-4 lg:px-0">
		<hr style="background: #1F3564; opacity: 0.33; height: 2px; margin-bottom: 1rem;" />
		<div class="pt-6 text-blue-600 dark:text-white">

			<div class="flex flex-wrap md:justify-between md:flex-no-wrap m-auto">
				<div class="flex flex-row mx-auto mx-0 w-full">

					<a href="/" class="flex pt-4 pr-2 no-underline">
						<Icon
								name="logo"
								class="cursor-pointer hover:opacity-75 bg-"
								title="Kingsley Omin Logo"
						/>
						<span class="inline-flex text-4xl font-extrabold -ml-5 -mt-4 text-blue-600 dark:text-white">O</span>
					</a>

					<ul class="flex flex-row justify-between md:justify-start mt-4 lg:mb-0 ml-6 md:ml-16 lg:ml-24 w-full text-sm sm:text-base">
						<li class="">
							<router-link
									class="py-2 block md:inline-block mx-2 sm:mx-4 no-underline text-blue-600 dark:text-white hover:text-blue-700"
									:to="{ name: 'works' }"
									active-class="text-yellow-600"
									exact>
								Works
							</router-link>
						</li>

						<li class="">
							<router-link
									class="py-2 block md:inline-block mx-2 sm:mx-4 no-underline text-blue-600 dark:text-white  hover:text-blue-700"
									:to="{ name: 'about' }"
									active-class="text-yellow-600"
									exact>
								About <span class="hidden sm:inline-flex">Me</span>
							</router-link>
						</li>

						<li class="">
							<router-link
									class="py-2 block md:inline-block mx-2 sm:mx-4 no-underline text-blue-600 dark:text-white hover:text-blue-700"
									:to="{ name: 'contact' }"
									active-class="text-yellow-600"
									exact>
								Contact
							</router-link>
						</li>
					</ul>
				</div>

				<div class="w-full sm:block lg:w-1/4 mt-6 md:mt-2 md:text-left pt-8 md:pt-0 text-sm sm:text-base" id="contact">
					<address>
						<a href="tel:+2347033218457" class="flex items-center no-underline">
							<Icon
									name="call"
									class="cursor-pointer hover:opacity-75 dark:text-white mt-2"
									title="Call"
							/>
							<span class="dark:text-white -mt-6 -ml-4">+234 703 321 8457</span>
						</a>
					</address>
					<address>
						<a href="mailto:kingsleyomin23@gmail.com" class="flex items-center no-underline">
							<Icon
									name="email"
									class="cursor-pointer hover:opacity-75 dark:text-white mt-2"
									title="Email"
							/>
							<span class="dark:text-white -mt-6 -ml-4">kingsleyomin23@gmail.com</span>
						</a>
					</address>
				</div>

			</div>
		</div>

		<div class="">
			<div class="flex pb-5 m-auto md:pt-5 flex-wrap lg:justify-between items-center">

				<div class="w-full lg:w-3/4 mt-2 text-center lg:text-left order-last lg:order-first">
					<p class="text-sm sm:text-base mt-4 lg:pt-0 text-blue-600 dark:text-white ">
						© 2020 Kingsley Omin. All Rights Reserved.
					</p>
				</div>

				<div class="w-full lg:w-1/5 pb-6 md:pb-0">
					<div class="md:flex-auto mt-2 flex-row flex justify-center lg:justify-start">

						<ul class="flex justify-start md:justify-end list-reset m-0 w-full md:w-auto">
							<li>
								<a href="/" class="block md:inline-block no-underline">
									<Icon
											name="dribble"
											class="cursor-pointer hover:opacity-75"
											title="Dribble"
									/>
								</a>
							</li>

							<li>
								<a href="/" class="block md:inline-block no-underline">
									<Icon
											name="linked-in"
											class="cursor-pointer hover:opacity-75"
											title="Linked-in"
									/>
								</a>
							</li>

							<li>
								<a href="/" class="block md:inline-block no-underline">
									<Icon
											name="twitter"
											class="cursor-pointer hover:opacity-75"
											title="Twitter"
									/>
								</a>
							</li>

							<li class="">
								<a href="/" class="block md:inline-block no-underline">
									<Icon
											name="medium"
											class="cursor-pointer hover:opacity-75"
											title="Medium"
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
		line-height: 20px;
		letter-spacing: -0.08px;
		font-style: normal;
	}
</style>
