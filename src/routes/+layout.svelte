<script lang="ts">
import '@fontsource/questrial'import '@fontsource/fira-code'
import Footer from '$lib/components/footer.svelte'import Header from '$lib/components/header.svelte'
</script>

<Header />
<main><slot /></main>
<Footer />

<style>
	main {
		padding: var(--size-2);
		min-height: 75svh;
	}
</style>
