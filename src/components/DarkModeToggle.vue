<template>
	<div>
		<Icon
				@click="toggleDarkMode"
				v-show="!isDarkMode"
				name="light-switch"
				class="cursor-pointer hover:opacity-75 pb-8 pt-2"
				title="switch"
				width="30"
		/>
		<Icon
				@click="toggleDarkMode"
				v-show="isDarkMode"
				name="dark-switch"
				class="cursor-pointer hover:opacity-75 pb-8 pt-2"
				title="switch"
				width="30"
		/>
	</div>
</template>

<script>
	import Icon from "../assets/icons/Icon";

	export default {
		name: "DarkModeToggle",
		components: {
			Icon
		},
		data() {
			return {
				isDarkMode: false,
			}
		},
		mounted() {
			if (this.checkDarkMode()) {
				this.addDarkSelector();
			}
		},
		methods: {
			checkDarkMode() {
				return (
						window.matchMedia &&
						window.matchMedia("(prefers-color-scheme: dark)").matches
				);
			},
			addDarkSelector() {
				this.isDarkMode = true;
				document.documentElement.classList.add("mode-dark");
			},

			removeDarkSelector() {
				this.isDarkMode = false;
				document.documentElement.classList.remove("mode-dark");
			},
			toggleDarkMode() {
				if (this.isDarkMode) {
					this.removeDarkSelector();
				} else {
					this.addDarkSelector();
				}
			}
		},
	}
</script>
