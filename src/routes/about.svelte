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
	<title>RyanLaBouve: About</title>
</svelte:head>

<div
	class="max-w-7xl mx-auto py-16 px-4 prose lg:prose-xl dark:prose-invert lg:grid grid-cols-3  gap-12"
>
	<div class="">
		<div class="tri w-60 h-60 bg-red-400 lg:mt-24 m-auto lg:ml-auto lg:mr-0" />
	</div>
	<div class="col-span-2 lg:max-w-2xl">
		<p>A little about me</p>
		<h3>Faith</h3>
		<p>
			Man had fallen. Jesus redeemed us. So I follow him. I'm not perfect but I do my best. Not here
			to get preachy, but if this page is about me, that's how it's gotta start.
		</p>
		<h3>Myself</h3>
		<p>Family Man. Got kids and a wife and I'm lucky to have them.</p>
		<p>
			<span>My Purpose—</span>Fighting disasters is what keeps me up at night and gets me up in the
			morning.
		</p>
		<p>
			<span>My Profession—</span>Computers pays the bills. I'm always building something. Hopefully
			it's the future.
		</p>
	</div>
</div>

<style>
	.tri {
		/* https://bennettfeely.com/clippy/ */
		clip-path: polygon(50% 0%, 100% 50%, 50% 100%, 0% 50%);
		background-image: url('/images/bio.png');
		background-size: contain;
		filter: saturate(25%);
	}
</style>
