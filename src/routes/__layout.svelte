<script>
	import "../app.css";
	import "../lib/header/Header.svelte";
	import Sidebar from "$lib/sidebar/Sidebar.svelte";
</script>

<Sidebar />

<main>
	<slot />
</main>

<footer>
	<p>
		visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to learn SvelteKit
	</p>
</footer>

<style>
	:global(body) {
		background-color: indianred;
		padding: 0 3em;
	}
</style>
