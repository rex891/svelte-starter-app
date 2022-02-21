<script lang="ts">
	export let name: string;
</script>

<template lang="pug">
	main.text-center.p-4
		h1.text-red-700.text-4xl.uppercase Hello {name}!
		p
			| Visit the 
			a(href="https://svelte.dev/tutorial") Svelte tutorial 
			| to learn how to build Svelte apps.
</template>

<style lang="postcss" global>
	@tailwind base;
	@tailwind components;
	@tailwind utilities;

</style>