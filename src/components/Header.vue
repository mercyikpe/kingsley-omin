<template>
	<div>
		<header id="header" class="relative h-auto mx-auto overflow-x-hidden overflow-y-visible font-medium">
			<nav class="mx-auto px-2 sm:px-6 md:px-10">
				<div class="mx-auto border-b border-gray-200 md:border-none pt-4 md:py-4 pb-2">
					<div class="flex flex-wrap items-center justify-between lg:justify-start w-full">

						<div class="">
							<router-link to="/" class="flex items-center pr-2 no-underline hover:opacity-75">
                                <svg width="58" height="37" fill="none" xmlns="http://www.w3.org/2000/svg">
                                    <path d="M0 .51A.51.51 0 01.51 0H8.68a.51.51 0 01.51.51v27.057a.51.51 0 01-.51.51H.51a.51.51 0 01-.511-.51V.511z" fill="#FFB22A"/>
                                    <path d="M8.64 14.293a.51.51 0 01.07-.718l6.31-5.186a.51.51 0 01.72.072l22.38 27.462a.51.51 0 01-.396.834H27.298a.51.51 0 01-.394-.187L8.64 14.293z" fill="#FFB22A"/>
                                    <path d="M15.803.348a.51.51 0 01.43-.235h10.258a.51.51 0 01.425.792L9.151 27.762a.51.51 0 01-.703.148l-6.872-4.428a.51.51 0 01-.153-.705L15.803.347z" fill="#FFB22A"/>
                                    <path d="M43.433 21.086c-3.383 0-5.525-2.518-5.525-7.104v-.3c0-4.586 2.142-7.03 5.45-7.03 3.383 0 5.563 2.481 5.563 7.03v.3c0 4.473-2.143 7.104-5.488 7.104zm-.225 6.69c8.832 0 14.583-5.6 14.583-13.982v-.3C57.791 4.998 51.627 0 43.358 0 35.315 0 29 5.412 29 13.719v.3c0 8.157 5.412 13.757 14.208 13.757z" class="fill-current text-blue-700 dark:text-white" fill="CurrentColor"/>
                                </svg>
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
								<ul class="flex justify-end list-reset -mx-1">
									<li class="border-t md:border-none mx-2">
										<a href="/" class="block md:inline-block no-underline">
                                            <svg class="hover:opacity-75" width="28" height="28" fill="none" xmlns="http://www.w3.org/2000/svg">
                                                <rect width="28" height="28" rx="2" class="fill-current text-yellow-600" fill="CurrentColor"/>
                                                <path class="fill-current text-white dark:text-black" d="M21.989 13.572a7.96 7.96 0 00-1.573-4.351c-.288.31-.595.6-.92.87-1 .83-2.115 1.507-3.313 2.01.167.35.32.689.455 1.009v.003c.038.09.075.18.11.27 1.514-.17 3.11-.108 4.657.101.206.028.4.058.584.088zm-9.385-7.45a46.175 46.175 0 012.692 4.27c1.223-.482 2.234-1.09 3.048-1.767.283-.233.548-.485.796-.755A7.968 7.968 0 0014 6c-.468 0-.935.04-1.396.121v.001zm-6.351 5.875a29.205 29.205 0 002.04-.123 31.535 31.535 0 004.862-.822 54.354 54.354 0 00-2.7-4.227 8.018 8.018 0 00-4.202 5.172zm1.53 7.038c.388-.567.898-1.205 1.575-1.899 1.454-1.49 3.17-2.65 5.156-3.29l.062-.018c-.165-.364-.32-.689-.476-.995-1.836.535-3.77.869-5.697 1.042-.94.085-1.783.122-2.403.128a7.967 7.967 0 001.784 5.032h-.001zm9.222 2.38a35.945 35.945 0 00-1.632-5.709c-2.002.727-3.597 1.79-4.83 3.058a9.77 9.77 0 00-1.317 1.655A7.964 7.964 0 0014 22a7.976 7.976 0 003.005-.583v-.002zm1.873-1.075a7.998 7.998 0 002.987-4.87c-.34-.085-.771-.17-1.245-.236a12.02 12.02 0 00-3.18-.033 39.36 39.36 0 011.438 5.14v-.001zM14 24C8.477 24 4 19.523 4 14S8.477 4 14 4s10 4.477 10 10-4.477 10-10 10z" fill="CurrentColor"/>
                                            </svg>
										</a>
									</li>

									<li class="border-t md:border-none mx-1">
										<a href="/" class="block md:inline-block no-underline">
                                            <svg class="hover:opacity-75" width="28" height="28" fill="none" xmlns="http://www.w3.org/2000/svg">
                                                <rect width="28" height="28" rx="2" class="fill-current text-yellow-600" fill="CurrentColor"/>
                                                <path class="fill-current text-white dark:text-black" d="M8.79 6.896A1.895 1.895 0 115 6.894a1.895 1.895 0 013.79.002zm.057 3.297h-3.79v11.864h3.79V10.193zm5.988 0h-3.77v11.864h3.732V15.83c0-3.468 4.52-3.79 4.52 0v6.226h3.743v-7.514c0-5.847-6.69-5.629-8.262-2.758l.037-1.592z" fill="CurrentColor"/>
                                            </svg>
										</a>
									</li>

									<li class="border-t md:border-none mx-1">
										<a href="/" class="block md:inline-block no-underline">
                                            <svg class="hover:opacity-75" width="28" height="28" fill="none" xmlns="http://www.w3.org/2000/svg">
                                                <rect width="28" height="28" rx="2" class="fill-current text-yellow-600" fill="CurrentColor"/>
                                                <path d="M23 8.55a7.402 7.402 0 01-2.122.581 3.705 3.705 0 001.625-2.043 7.38 7.38 0 01-2.346.896 3.693 3.693 0 00-6.292 3.368 10.484 10.484 0 01-7.612-3.859 3.693 3.693 0 001.143 4.931 3.68 3.68 0 01-1.673-.462v.046a3.696 3.696 0 002.963 3.622 3.717 3.717 0 01-1.67.063 3.695 3.695 0 003.45 2.566A7.412 7.412 0 015 19.788a10.447 10.447 0 005.66 1.66c6.794 0 10.509-5.628 10.509-10.508 0-.16-.005-.32-.012-.477A7.501 7.501 0 0023 8.551z" class="fill-current text-white dark:text-black" fill="CurrentColor"/>
                                            </svg>
										</a>
									</li>

									<li class="border-t md:border-none mx-1">
										<a href="/" class="block md:inline-block no-underline">
                                            <svg class="hover:opacity-75" width="28" height="28" viewBox="0 0 28 28" fill="none" xmlns="http://www.w3.org/2000/svg">
                                                <rect width="28" height="28" rx="2" class="fill-current text-yellow-600" fill="CurrentColor"/>
                                                <path class="fill-current text-white dark:text-black" d="M6 5H22C22.2652 5 22.5196 5.10536 22.7071 5.29289C22.8946 5.48043 23 5.73478 23 6V22C23 22.2652 22.8946 22.5196 22.7071 22.7071C22.5196 22.8946 22.2652 23 22 23H6C5.73478 23 5.48043 22.8946 5.29289 22.7071C5.10536 22.5196 5 22.2652 5 22V6C5 5.73478 5.10536 5.48043 5.29289 5.29289C5.48043 5.10536 5.73478 5 6 5ZM7 7V21H21V7H7ZM19.3 17.94L20.255 18.894V18.944H15.334V18.894L16.338 17.94C16.438 17.84 16.488 17.74 16.488 17.589V11.664C16.488 11.412 16.488 11.061 16.539 10.76L13.225 19.045H13.175L9.76 11.412C9.71 11.212 9.66 11.212 9.61 11.112V16.132C9.559 16.484 9.61 16.785 9.76 17.087L11.116 18.894V18.944H7.5V18.894L8.856 17.036C9.006 16.736 9.056 16.384 9.006 16.082V10.56C9.006 10.309 8.956 10.007 8.756 9.807L7.851 8.55V8.5H11.366L14.278 14.978L16.84 8.5H20.255V8.55L19.301 9.655C19.201 9.755 19.151 9.906 19.151 10.006V17.639C19.151 17.739 19.201 17.89 19.301 17.94H19.3Z" fill="#222222"/>
                                            </svg>
										</a>
									</li>
								</ul>
							</div>
						</div>

						<div class="block lg:hidden" style=" right: -1.5rem; top: 1rem;">
							<button
									@click="openNav()"
									id="ham"
									class="hover:opacity-75">
                                <svg width="24" height="24" fill="none" xmlns="http://www.w3.org/2000/svg">
                                    <path class="fill-current text-gray-1000 dark:text-white" d="M3 18h18v-2H3v2zm0-5h18v-2H3v2zm0-7v2h18V6H3z" fill="CurrentColor"/>
                                </svg>
							</button>
						</div>
					</div>
				</div>
			</nav>

			<div ref="myNav" class="flex flex-col min-h-screen overflow-hidden shadow-lg text-base font-medium bg-white dark:bg-black overlay">
				<div class="p-8 bg-white dark:bg-black">
					<!-- button to close the overlay -->
					<div class="flex justify-between items-center">
						<router-link to="/" class="flex items-center pr-2 no-underline hover:opacity-75">
                            <svg width="58" height="37" fill="none" xmlns="http://www.w3.org/2000/svg">
                                <path d="M0 .51A.51.51 0 01.51 0H8.68a.51.51 0 01.51.51v27.057a.51.51 0 01-.51.51H.51a.51.51 0 01-.511-.51V.511z" fill="#FFB22A"/>
                                <path d="M8.64 14.293a.51.51 0 01.07-.718l6.31-5.186a.51.51 0 01.72.072l22.38 27.462a.51.51 0 01-.396.834H27.298a.51.51 0 01-.394-.187L8.64 14.293z" fill="#FFB22A"/>
                                <path d="M15.803.348a.51.51 0 01.43-.235h10.258a.51.51 0 01.425.792L9.151 27.762a.51.51 0 01-.703.148l-6.872-4.428a.51.51 0 01-.153-.705L15.803.347z" fill="#FFB22A"/>
                                <path d="M43.433 21.086c-3.383 0-5.525-2.518-5.525-7.104v-.3c0-4.586 2.142-7.03 5.45-7.03 3.383 0 5.563 2.481 5.563 7.03v.3c0 4.473-2.143 7.104-5.488 7.104zm-.225 6.69c8.832 0 14.583-5.6 14.583-13.982v-.3C57.791 4.998 51.627 0 43.358 0 35.315 0 29 5.412 29 13.719v.3c0 8.157 5.412 13.757 14.208 13.757z" class="fill-current text-blue-700 dark:text-white" fill="CurrentColor"/>
                            </svg>
						</router-link>

						<button class="closebtn -mr-4 relative hover:opacity-75" @click="closeNav()">
                            <svg class="" width="24" height="24" fill="none" xmlns="http://www.w3.org/2000/svg">
                                <path class="fill-current text-blue-600 dark:text-white" d="M19 6.41L17.59 5 12 10.59 6.41 5 5 6.41 10.59 12 5 17.59 6.41 19 12 13.41 17.59 19 19 17.59 13.41 12 19 6.41z" fill="#CurrentColor"/>
                            </svg>
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


                        <ul class="flex justify-start list-reset -mx-1">

                            <li class="border-t md:border-none mx-2">
                                <a href="/" class="block md:inline-block no-underline">
                                    <svg class="hover:opacity-75" width="28" height="28" fill="none" xmlns="http://www.w3.org/2000/svg">
                                        <rect width="28" height="28" rx="2" class="fill-current text-yellow-600" fill="CurrentColor"/>
                                        <path class="fill-current text-white dark:text-black" d="M21.989 13.572a7.96 7.96 0 00-1.573-4.351c-.288.31-.595.6-.92.87-1 .83-2.115 1.507-3.313 2.01.167.35.32.689.455 1.009v.003c.038.09.075.18.11.27 1.514-.17 3.11-.108 4.657.101.206.028.4.058.584.088zm-9.385-7.45a46.175 46.175 0 012.692 4.27c1.223-.482 2.234-1.09 3.048-1.767.283-.233.548-.485.796-.755A7.968 7.968 0 0014 6c-.468 0-.935.04-1.396.121v.001zm-6.351 5.875a29.205 29.205 0 002.04-.123 31.535 31.535 0 004.862-.822 54.354 54.354 0 00-2.7-4.227 8.018 8.018 0 00-4.202 5.172zm1.53 7.038c.388-.567.898-1.205 1.575-1.899 1.454-1.49 3.17-2.65 5.156-3.29l.062-.018c-.165-.364-.32-.689-.476-.995-1.836.535-3.77.869-5.697 1.042-.94.085-1.783.122-2.403.128a7.967 7.967 0 001.784 5.032h-.001zm9.222 2.38a35.945 35.945 0 00-1.632-5.709c-2.002.727-3.597 1.79-4.83 3.058a9.77 9.77 0 00-1.317 1.655A7.964 7.964 0 0014 22a7.976 7.976 0 003.005-.583v-.002zm1.873-1.075a7.998 7.998 0 002.987-4.87c-.34-.085-.771-.17-1.245-.236a12.02 12.02 0 00-3.18-.033 39.36 39.36 0 011.438 5.14v-.001zM14 24C8.477 24 4 19.523 4 14S8.477 4 14 4s10 4.477 10 10-4.477 10-10 10z" fill="CurrentColor"/>
                                    </svg>
                                </a>
                            </li>

                            <li class="border-t md:border-none mx-1">
                                <a href="/" class="block md:inline-block no-underline">
                                    <svg class="hover:opacity-75" width="28" height="28" fill="none" xmlns="http://www.w3.org/2000/svg">
                                        <rect width="28" height="28" rx="2" class="fill-current text-yellow-600" fill="CurrentColor"/>
                                        <path class="fill-current text-white dark:text-black" d="M8.79 6.896A1.895 1.895 0 115 6.894a1.895 1.895 0 013.79.002zm.057 3.297h-3.79v11.864h3.79V10.193zm5.988 0h-3.77v11.864h3.732V15.83c0-3.468 4.52-3.79 4.52 0v6.226h3.743v-7.514c0-5.847-6.69-5.629-8.262-2.758l.037-1.592z" fill="CurrentColor"/>
                                    </svg>
                                </a>
                            </li>

                            <li class="border-t md:border-none mx-1">
                                <a href="/" class="block md:inline-block no-underline">
                                    <svg class="hover:opacity-75" width="28" height="28" fill="none" xmlns="http://www.w3.org/2000/svg">
                                        <rect width="28" height="28" rx="2" class="fill-current text-yellow-600" fill="CurrentColor"/>
                                        <path d="M23 8.55a7.402 7.402 0 01-2.122.581 3.705 3.705 0 001.625-2.043 7.38 7.38 0 01-2.346.896 3.693 3.693 0 00-6.292 3.368 10.484 10.484 0 01-7.612-3.859 3.693 3.693 0 001.143 4.931 3.68 3.68 0 01-1.673-.462v.046a3.696 3.696 0 002.963 3.622 3.717 3.717 0 01-1.67.063 3.695 3.695 0 003.45 2.566A7.412 7.412 0 015 19.788a10.447 10.447 0 005.66 1.66c6.794 0 10.509-5.628 10.509-10.508 0-.16-.005-.32-.012-.477A7.501 7.501 0 0023 8.551z" class="fill-current text-white dark:text-black" fill="CurrentColor"/>
                                    </svg>
                                </a>
                            </li>

                            <li class="border-t md:border-none mx-1">
                                <a href="/" class="block md:inline-block no-underline">
                                    <svg class="hover:opacity-75" width="28" height="28" viewBox="0 0 28 28" fill="none" xmlns="http://www.w3.org/2000/svg">
                                        <rect width="28" height="28" rx="2" class="fill-current text-yellow-600" fill="CurrentColor"/>
                                        <path class="fill-current text-white dark:text-black" d="M6 5H22C22.2652 5 22.5196 5.10536 22.7071 5.29289C22.8946 5.48043 23 5.73478 23 6V22C23 22.2652 22.8946 22.5196 22.7071 22.7071C22.5196 22.8946 22.2652 23 22 23H6C5.73478 23 5.48043 22.8946 5.29289 22.7071C5.10536 22.5196 5 22.2652 5 22V6C5 5.73478 5.10536 5.48043 5.29289 5.29289C5.48043 5.10536 5.73478 5 6 5ZM7 7V21H21V7H7ZM19.3 17.94L20.255 18.894V18.944H15.334V18.894L16.338 17.94C16.438 17.84 16.488 17.74 16.488 17.589V11.664C16.488 11.412 16.488 11.061 16.539 10.76L13.225 19.045H13.175L9.76 11.412C9.71 11.212 9.66 11.212 9.61 11.112V16.132C9.559 16.484 9.61 16.785 9.76 17.087L11.116 18.894V18.944H7.5V18.894L8.856 17.036C9.006 16.736 9.056 16.384 9.006 16.082V10.56C9.006 10.309 8.956 10.007 8.756 9.807L7.851 8.55V8.5H11.366L14.278 14.978L16.84 8.5H20.255V8.55L19.301 9.655C19.201 9.755 19.151 9.906 19.151 10.006V17.639C19.151 17.739 19.201 17.89 19.301 17.94H19.3Z" fill="#222222"/>
                                    </svg>
                                </a>
                            </li>
                        </ul>

						<div class="flex items-center my-6">
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
	import DarkModeToggle from "./DarkModeToggle";

	export default {
		data() {
			return {
				isOpen: false
			};
		},
			components: {
							DarkModeToggle,
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
