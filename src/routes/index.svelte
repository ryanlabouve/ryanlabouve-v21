<script context="module" lang="ts">
	export const prerender = true;
</script>

<script lang="ts">
	import Counter from '$lib/Counter.svelte';
</script>

<svelte:head>
	<title>Home</title>
</svelte:head>

<div class="max-w-7xl mx-auto py-16 px-4">
	<div class="bg-gray-800 rounded-lg shadow-xl overflow-hidden lg:grid lg:grid-cols-2 lg:gap-4">
		<div class="pt-10 pb-12 px-6 sm:pt-16 sm:px-16 lg:py-16 lg:pr-0 xl:py-20 xl:px-20">
			<div class="lg:self-center">
				<h2 class="text-3xl font-extrabold text-white sm:text-4xl">
					<span class="block">Combat Disasters</span>
					<span class="block">Security & Web3</span>
				</h2>
				<p class="mt-4 text-lg leading-6 text-indigo-200">
					I'm a software engineer who has spent the past few years diving into disaster relief,
					security, and web3.
				</p>
			</div>
		</div>
		<div class="-mt-6 aspect-w-5 aspect-h-3 md:aspect-w-2 md:aspect-h-1" />
	</div>
</div>
