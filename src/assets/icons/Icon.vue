<template>
	<div
			class="inline-block align-middle"
			@click="$emit('click', $event)"
			v-html="
			require(`@/assets/icons/${name}.svg`)
		"
	></div>
</template>

<style>
	.svg {
		fill: currentColor;
		vertical-align: middle;
	}

	.fill-current {
		fill: currentColor;
	}
</style>

<script>
	export default {
		props: ["name"],

		mounted() {
			const svg = this.$el.querySelector("svg");
			const width = this.$attrs.width || 16;
			const height = this.$attrs.height || width || 16;
			svg.setAttribute("height", width);
			svg.setAttribute("width", height);
			svg.classList.add(...["fill-current", "svg"]);
		},
	};
</script>
