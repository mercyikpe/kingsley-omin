<template>
	<nav class="nav flex flex-wrap items-center justify-between">
		<div class="mb-2 sm:mb-0 flex flex-row">
			<div>
				<a href="/" class="">
					<img class="h-10 w-16 self-center" src="https://res.cloudinary.com/mercyikpe/image/upload/v1596667405/kingsley%20omin/favicon.png" alt="logo" />
				</a>
			</div>

			<!-- navbar links-->
			<ul class="ml-24 menu border-b md:border-none flex items-end list-reset m-0 w-full md:w-auto">
				<li class="border-t md:border-none">
					<a href="/" class="block md:inline-block mx-4 border-b-2 border-yellow-600 text-yellow-600 font-medium">
						Home
					</a>
				</li>

				<li class="border-t md:border-none">
					<a href="/" class="block md:inline-block mx-4 no-underline text-blue-600 hover:text-blue-700 font-medium">
						Work
					</a>
				</li>

				<li class="border-t md:border-none">
					<a href="/" class="block md:inline-block mx-4 no-underline text-blue-600 hover:text-blue-700 font-medium">
						About Me
					</a>
				</li>

				<li class="border-t md:border-none">
					<a href="/" class="block md:inline-block mx-4 no-underline text-blue-600 hover:text-blue-700 font-medium">
						Contact
					</a>
				</li>

			</ul>
		</div>

		<ul class="menu border-b md:border-none flex justify-end list-reset m-0 w-full md:w-auto">
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
	</nav>
</template>

<script>
	import Icon from "../assets/icons/Icon";
	export default {
		name: "NavBar",
		components: {
			Icon
		}
	}
</script>

<style scoped>

</style>
<style>
	@media (max-width: 767px) {
		.navicon {
			width: 1.125em;
			height: .125em;
		}

		.navicon::before,
		.navicon::after {
			display: block;
			position: absolute;
			width: 100%;
			height: 100%;
			transition: all .2s ease-out;
			content: '';
			background: #3D4852;
		}

		.navicon::before {
			top: 5px;
		}

		.navicon::after {
			top: -5px;
		}

		.menu-btn:not(:checked) ~ .menu {
			display: none;
		}

		.menu-btn:checked ~ .menu {
			display: block;
		}

		.menu-btn:checked ~ .menu-icon .navicon {
			background: transparent;
		}

		.menu-btn:checked ~ .menu-icon .navicon::before {
			transform: rotate(-45deg);
		}

		.menu-btn:checked ~ .menu-icon .navicon::after {
			transform: rotate(45deg);
		}

		.menu-btn:checked ~ .menu-icon .navicon::before,
		.menu-btn:checked ~ .menu-icon .navicon::after {
			top: 0;
		}
	}
	/*.fa-2x {*/
	/*	font-size: 4em;*/
	/*}*/
</style>
