<script context="module" lang="ts">
	export const prerender = true;
</script>

<script lang="ts">
	import Counter from '$lib/Counter.svelte';
</script>

<svelte:head>
	<title>RyanLaBouve.com</title>
</svelte:head>

<div class="max-w-7xl mx-auto py-16 px-4">
	<div class=" rounded-lg shadow-xl overflow-hidden lg:grid lg:grid-cols-2 lg:gap-0">
		<div class=" bg-gray-800 pt-10 pb-12 px-6 sm:pt-16 sm:px-16 lg:py-16 lg:pr-0 xl:py-20 xl:px-20">
			<div class="lg:self-center">
				<h2 class="text-3xl font-extrabold text-white sm:text-4xl">
					<span class="block heading">Disasters & Demolition</span>
				</h2>
				<p class="mt-4 text-lg leading-6 text-indigo-200">
					I'm a software engineer who has spent the past few years diving into disaster relief,
					security, and web3.
				</p>
			</div>
			<a
				href="#"
				class="mt-6 inline-flex items-center justify-center px-5 py-3 border border-transparent text-base font-medium rounded-md text-gray-900 bg-white hover:bg-gray-50"
			>
				Disasters
				<svg
					xmlns="http://www.w3.org/2000/svg"
					class="h-6 w-6 ml-1"
					fill="none"
					viewBox="0 0 24 24"
					stroke="currentColor"
				>
					<path
						stroke-linecap="round"
						stroke-linejoin="round"
						stroke-width="2"
						d="M17.657 18.657A8 8 0 016.343 7.343S7 9 9 10c0-2 .5-5 2.986-7C14 5 16.09 5.777 17.656 7.343A7.975 7.975 0 0120 13a7.975 7.975 0 01-2.343 5.657z"
					/>
					<path
						stroke-linecap="round"
						stroke-linejoin="round"
						stroke-width="2"
						d="M9.879 16.121A3 3 0 1012.015 11L11 14H9c0 .768.293 1.536.879 2.121z"
					/>
				</svg>
			</a>
		</div>
		<div
			class="bg-indigo-900 pt-10 pb-12 px-6 sm:pt-16 sm:px-16 lg:py-16 lg:pr-0 xl:py-20 xl:px-20"
		>
			<div class="lg:self-center">
				<h2 class="text-3xl font-extrabold text-white sm:text-4xl">
					<span class="block heading">Security & Web3</span>
				</h2>
				<p class="mt-4 text-lg leading-6 text-indigo-200">
					I'm a software engineer who has spent the past few years diving into disaster relief,
					security, and web3.
				</p>
			</div>
			<a
				href="#"
				class="mt-6 inline-flex items-center justify-center px-5 py-3 border border-transparent text-base font-medium rounded-md text-gray-900 bg-white hover:bg-gray-50"
			>
				Read more
				<svg
					xmlns="http://www.w3.org/2000/svg"
					class="h-5 w-5 ml-1"
					viewBox="0 0 20 20"
					fill="currentColor"
				>
					<path
						d="M10.394 2.08a1 1 0 00-.788 0l-7 3a1 1 0 000 1.84L5.25 8.051a.999.999 0 01.356-.257l4-1.714a1 1 0 11.788 1.838L7.667 9.088l1.94.831a1 1 0 00.787 0l7-3a1 1 0 000-1.838l-7-3zM3.31 9.397L5 10.12v4.102a8.969 8.969 0 00-1.05-.174 1 1 0 01-.89-.89 11.115 11.115 0 01.25-3.762zM9.3 16.573A9.026 9.026 0 007 14.935v-3.957l1.818.78a3 3 0 002.364 0l5.508-2.361a11.026 11.026 0 01.25 3.762 1 1 0 01-.89.89 8.968 8.968 0 00-5.35 2.524 1 1 0 01-1.4 0zM6 18a1 1 0 001-1v-2.065a8.935 8.935 0 00-2-.712V17a1 1 0 001 1z"
					/>
				</svg>
			</a>
		</div>
	</div>
</div>
