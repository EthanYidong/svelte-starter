<script lang="ts">
	import Tailwind from './Tailwind.svelte';
	export let name: string;
</script>

<Tailwind />
<main>
	<h1>Hello {name}!</h1>
	<p>Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.</p>
</main>

<style>
	h1 {
		@apply text-2xl;
	}
</style>