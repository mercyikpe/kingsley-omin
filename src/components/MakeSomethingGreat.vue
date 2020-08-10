<template>
	<div class="my-32">
		<div class="max-w-6xl mx-auto py-24 px-8 bg-yellow-700 text-white rounded-lg flex">
			<Icon
					name="quote"
					class="cursor-pointer hover:opacity-75"
					title="Logo"
					width="60"
			/>
			<div class="text-left w-full ml-6">
				<h2 class="text-7xl font-semibold text-left tracking-wide">Let’s make <br> something Great <br>Together</h2>

				<a href="mailto:kingsleyomin23@gmail.com" class="mt-8 block md:inline-block text-2xl font-medium no-underline">
					<span class="mr-3">Email:</span> kingsleyomin23@gmail.com
				</a>
			</div>
		</div>
	</div>
</template>

<script>
	import Icon from "../assets/icons/Icon";
		export default {
		name: "MakeSomethingGreat",
					components: {Icon}
		}
</script>

<style scoped>

</style>
