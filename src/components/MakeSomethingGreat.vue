<template>
	<div class="max-w-full mx-auto py-16 lg:py-24 px-4 lg:px-8 flex mx-6 lg:mx-0">
			<Icon
					name="quote-sm"
					class="cursor-pointer hover:opacity-75 lg:hidden pt-2"
					title="Logo"
					width="20"
			/>
			<Icon
					name="quote"
					class="cursor-pointer hover:opacity-75 hidden lg-flex"
					title="Logo"
					width="60"
			/>
			<div class="text-left w-full ml-4 lg:ml-6">
				<h2 class="text-4xl lg:text-7xl font-semibold text-left tracking-wide leading-tight">Let’s make <br> something Great <br>Together</h2>

				<a href="mailto:kingsleyomin23@gmail.com" class="mt-8 block md:inline-block text-base lg:text-2xl font-medium no-underline">
					<span class="mr-1 lg:mr-3">Email:</span> kingsleyomin23@gmail.com
				</a>
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
