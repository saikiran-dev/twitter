<template>
	<div id="app">
		<Layout />
	</div>
</template>

<script>
import Layout from "./components/Layout.vue";

export default {
	name: "App",
	components: {
		Layout,
	},
};
</script>

<style>
.circle {
	@apply rounded-full h-10 w-10;
}

.button-class {
	@apply bg-twitter-thick text-white tracking-wide px-4 py-2 rounded-full;
}
</style>
