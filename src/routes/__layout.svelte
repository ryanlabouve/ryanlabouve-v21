<script lang="ts">
	import Header from '$lib/header/Header.svelte';
	import '../app.css';
</script>

<div class="dark:bg-gray-900 dark:text-gray-200 " style="min-height: 100vh;">
	<Header />

	<main>
		<slot />
	</main>

	<footer class="p-4 text-center">&copy;RyanLaBouve 2021</footer>
</div>
