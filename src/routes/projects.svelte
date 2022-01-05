<script context="module">
	import { browser, dev } from '$app/env';

	// we don't need any JS on this page, though we'll load
	// it in dev so that we get hot module replacement...
	export const hydrate = dev;

	// ...but if the client-side router is already loaded
	// (i.e. we came here from elsewhere in the app), use it
	export const router = browser;

	// since there's no dynamic data here, we can prerender
	// it so that it gets served as a static asset in prod
	export const prerender = true;
</script>

<svelte:head>
	<title>RyanLaBouve: Projects</title>
</svelte:head>

<div class="max-w-7xl mx-auto py-16 px-4 prose text-gray-400 lg:grid grid-cols-3 gap-3">
	<div>Projects</div>
</div>
