<template>
	<div>
		<header id="header" class="relative h-auto mx-auto overflow-x-hidden overflow-y-visible font-medium">
			<nav class="mx-auto">
				<div class="mx-auto border-b border-gray-200 md:border-none pt-4 md:py-4">
					<div class="flex flex-wrap items-center justify-between lg:justify-start w-full">

						<div class="">
							<router-link to="/" class="flex items-center pr-2 no-underline">
								<Icon
										name="logo"
										class="cursor-pointer hover:opacity-75"
										title="Logo"
								/>
								<span class="inline-flex text-4xl font-extrabold -ml-5 -mt-4 text-blue-600 dark:text-white">O</span>
							</router-link>

						</div>

						<!-- navbar links-->
						<div class="hidden lg:flex flex-1 justify-between">
							<div class="ml-24">
								<router-link
										class="inline-block mx-4 no-underline text-blue-600 hover:text-blue-700 dark:text-white font-medium"
										:to="{ name: 'home' }"
										exact-active-class="border-b-2 border-yellow-600 text-yellow-600 dark:text-yellow-600">
									Home
								</router-link>

								<router-link
										class="inline-block mx-4 no-underline text-blue-600 hover:text-blue-700 dark:text-white font-medium"
										:to="{ name: 'works' }"
										exact-active-class="border-b-2 border-yellow-600 text-yellow-600 dark:text-yellow-600">
									Works
								</router-link>

								<router-link
										class="inline-block mx-4 no-underline text-blue-600 hover:text-blue-700 dark:text-white font-medium"
										:to="{ name: 'about' }"
										exact-active-class="border-b-2 border-yellow-600 text-yellow-600 dark:text-yellow-600">
									About Me
								</router-link>

								<router-link
										class="inline-block mx-4 no-underline text-blue-600 hover:text-blue-700 dark:text-white font-medium"
										:to="{ name: 'contact' }"
										exact-active-class="border-b-2 border-yellow-600 text-yellow-600 dark:text-yellow-600">
									Contact
								</router-link>
							</div>

							<div>
								<ul class="flex justify-end list-reset">
									<li class="border-t md:border-none">
										<a href="/" class="block md:inline-block no-underline">
											<Icon
													name="dribble"
													class="cursor-pointer hover:opacity-75"
													title="Dribble"
											/>
										</a>
									</li>

									<li class="border-t md:border-none">
										<a href="/" class="block md:inline-block no-underline">
											<Icon
													name="linked-in"
													class="cursor-pointer hover:opacity-75"
													title="Linked-in"
											/>
										</a>
									</li>

									<li class="border-t md:border-none">
										<a href="/" class="block md:inline-block no-underline">
											<Icon
													name="twitter"
													class="cursor-pointer hover:opacity-75"
													title="Twitter"
											/>
										</a>
									</li>

									<li class="border-t md:border-none">
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

						<div class="block lg:hidden" style="position:relative; right: -1.5rem; top: 1rem;">
							<button
									@click="openNav()"
									id="ham"
									class="">
								<Icon
										name="open-nav"
										class="cursor-pointer hover:opacity-75"
										title="Open Menu"
								/>
							</button>
						</div>
					</div>
				</div>
			</nav>

			<div ref="myNav" class="flex flex-col min-h-screen overflow-hidden shadow-lg text-base font-medium bg-white dark:bg-black overlay">
				<div class="p-8 bg-white dark:bg-black">
					<!-- button to close the overlay -->
					<div class="flex justify-between items-center">
						<router-link to="/" class="flex items-center pr-2 no-underline">
							<Icon
									name="logo"
									class="cursor-pointer hover:opacity-75"
									title="Logo"
							/>
							<span class="inline-flex text-4xl font-extrabold -ml-5 -mt-4 text-blue-600 dark:text-white">O</span>
						</router-link>

						<button class="closebtn -mt-6 -mr-8 relative" @click="closeNav()">
							<Icon
									name="close-nav"
									class="absolute right-0 cursor-pointer hover:opacity-75"
									title="Close Menu"
							/>
						</button>
					</div>

					<!-- overlay content -->
					<div class="my-12">
						<router-link
								class="my-10 inline-block text-blue-600 dark:text-white hover:text-blue-700 font-medium"
								:to="{ name: 'home' }"
								active-class="text-yellow-600 dark:text-yellow-600"
								exact>
							Home
						</router-link>

						<router-link
								class="my-10 inline-block text-blue-600 dark:text-white hover:text-blue-700 font-medium"
								:to="{ name: 'works' }"
								active-class="text-yellow-600 dark:text-yellow-600"
								exact>
							Works
						</router-link>

						<router-link
								class="my-10 inline-block text-blue-600 dark:text-white hover:text-blue-700 font-medium"
								:to="{ name: 'about' }"
								active-class="text-yellow-600 dark:text-yellow-600"
								exact>
							About Me
						</router-link>

						<router-link
								class="my-10 inline-block text-blue-600 dark:text-white hover:text-blue-700 font-medium"
								:to="{ name: 'contact' }"
								active-class="text-yellow-600 dark:text-yellow-600"
								exact>
							Contact
						</router-link>

						<div class="flex items-center my-10">
							<div class="inline-flex mr-4 mt-6">
								<DarkModeToggle />
							</div>
							<p class="font-medium text-blue-800 dark:text-white">Switch View</p>
						</div>
					</div>
				</div>

			</div>

		</header>

		<div
				v-if="isOpen"
				@click="closeNav"
				class="absolute w-full top-0 left-0 w-full h-screen"
				style="background: #2A3D64; opacity: 0.5;">
		</div>
	</div>
</template>

<script>
	import Icon from "../assets/icons/Icon";
	import DarkModeToggle from "./DarkModeToggle";

	export default {
		data() {
			return {
				isOpen: false
			};
		},
			components: {
							DarkModeToggle,
				Icon
			},
		watch: {
			$route() {
				if (this.isOpen) {
					this.closeNav();
				}
			}
		},
		methods: {
			closeNav() {
				/* Close when someone clicks on the "x" symbol inside the overlay */
				this.$refs.myNav.style.width = '0%';
				this.isOpen = false;
			},
			openNav() {
				/* Open when someone clicks on the span element */
				this.$refs.myNav.style.width = '85%';
				this.isOpen = true;
			}
		}
	};
</script>
<style scoped>
	.overlay {
		/* Height & width depends on how you want to reveal the overlay  */
		height: 100%;
		width: 0;
		position: fixed; /* Stay in place */
		z-index: 99; /* Sit on top */
		left: 0;
		top: 0;
		overflow-x: hidden;
		transition: 0.3s;
	}
	/* The navigation links inside the overlay */
	.overlay a {
		text-decoration: none;
		display: block;
		transition: 0.3s;
	}
	*:focus {
		outline: none;
		box-shadow: none;
	}
</style>
