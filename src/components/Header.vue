<template>
	<div>
		<header id="header" class="relative h-auto mx-auto overflow-x-hidden overflow-y-visible font-medium">
			<nav class="mx-auto">
				<div class="mx-auto border-b border-gray-200 md:border-none py-4">
					<div class="flex flex-wrap items-center justify-between lg:justify-start w-full">

						<div class="">
							<router-link to="/">
								<img class="h-10 w-16 self-center" src="https://res.cloudinary.com/mercyikpe/image/upload/v1596667405/kingsley%20omin/favicon.png" alt="logo" />
							</router-link>
						</div>


						<!-- navbar links-->
						<div class="hidden lg:flex flex-1 justify-between">
							<div class="ml-24">
								<router-link
										class="inline-block mx-4 no-underline text-blue-600 hover:text-blue-700 font-medium"
										:to="{ name: 'home' }"
										active-class="border-b-2 border-yellow-600 text-yellow-600"
										exact>
									Home
								</router-link>

								<router-link
										class="inline-block mx-4 no-underline text-blue-600 hover:text-blue-700 font-medium"
										:to="{ name: 'works' }"
										active-class="border-b-2 border-yellow-600 text-yellow-600"
										exact>
									Work
								</router-link>

								<router-link
										class="inline-block mx-4 no-underline text-blue-600 hover:text-blue-700 font-medium"
										:to="{ name: 'about' }"
										active-class="border-b-2 border-yellow-600 text-yellow-600"
										exact>
									About Me
								</router-link>

								<router-link
										class="inline-block mx-4 no-underline text-blue-600 hover:text-blue-700 font-medium"
										:to="{ name: 'contact' }"
										active-class="border-b-2 border-yellow-600 text-yellow-600"
										exact>
									Contact
								</router-link>
							</div>

							<div>
								<ul class="flex justify-end list-reset">
									<li class="border-t md:border-none">
										<a href="/" class="block md:inline-block px-1 no-underline">
											<Icon
													name="dribble"
													class="fa-2x cursor-pointer hover:opacity-75"
													title="Logo"
													width="30"
											/>
										</a>
									</li>

									<li class="border-t md:border-none">
										<a href="/" class="block md:inline-block px-1 no-underline">
											<Icon
													name="linked-in"
													class="fa-2x cursor-pointer hover:opacity-75"
													title="Logo"
													width="30"
											/>
										</a>
									</li>

									<li class="border-t md:border-none">
										<a href="/" class="block md:inline-block px-1 no-underline">
											<Icon
													name="twitter"
													class="fa-2x cursor-pointer hover:opacity-75"
													title="Logo"
													width="30"
											/>
										</a>
									</li>

									<li class="border-t md:border-none">
										<a href="/" class="block md:inline-block pl-1 no-underline">
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

						<div class="block lg:hidden">
							<button
									@click="openNav()"
									id="ham"
									class="flex items-center py-2">
								<svg width="18" height="12" fill="none" xmlns="http://www.w3.org/2000/svg">
									<path d="M0 12h18v-2H0v2zm0-5h18V5H0v2zm0-7v2h18V0H0z" fill="#1D2029" />
								</svg>
							</button>
						</div>
					</div>
				</div>
			</nav>

			<div ref="myNav" class="flex flex-col min-h-screen overflow-hidden shadow-lg text-base font-medium bg-white overlay">
				<div class="p-8 bg-white">
					<!-- button to close the overlay -->
					<div class="flex justify-between">
						<router-link to="/">
							<img class="h-8 w-12 self-center" src="https://res.cloudinary.com/mercyikpe/image/upload/v1596667405/kingsley%20omin/favicon.png" alt="logo" />
						</router-link>

						<a class="closebtn" @click="closeNav()" href="#">
							<svg width="14" height="14" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path d="M14 1.41L12.59 0 7 5.59 1.41 0 0 1.41 5.59 7 0 12.59 1.41 14 7 8.41 12.59 14 14 12.59 8.41 7 14 1.41z" fill="#000"/>
							</svg>
						</a>
					</div>

					<!-- overlay content -->
					<div class="my-12">
						<router-link
								class="my-10 inline-block text-blue-600 hover:text-blue-700 font-medium"
								:to="{ name: 'home' }"
								active-class="text-yellow-600"
								exact>
							Home
						</router-link>

						<router-link
								class="my-10 inline-block text-blue-600 hover:text-blue-700 font-medium"
								:to="{ name: 'works' }"
								active-class="text-yellow-600"
								exact>
							Works
						</router-link>

						<router-link
								class="my-10 inline-block text-blue-600 hover:text-blue-700 font-medium"
								:to="{ name: 'about' }"
								active-class="text-yellow-600"
								exact>
							About Me
						</router-link>

						<router-link
								class="my-10 inline-block text-blue-600 hover:text-blue-700 font-medium"
								:to="{ name: 'contact' }"
								active-class="text-yellow-600"
								exact>
							Contact
						</router-link>

						<div class="flex items-center my-10">
							<Icon
									name="light-switch"
									class="cursor-pointer hover:opacity-75 mr-4"
									title="switch"
									width="30"
							/>
							<p class="font-medium text-blue-800">Switch View</p>
						</div>
					</div>
				</div>

			</div>

		</header>

		<button
				v-if="isOpen"
				@click="closeNav"
				class="absolute w-full top-0 left-0 w-full h-screen"
				style="background: #2A3D64; opacity: 0.5">

		</button>
	</div>
</template>

<script>
	import Icon from "../assets/icons/Icon";
	export default {
		data() {
			return {
				isOpen: false
			};
		},
			components: {
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
