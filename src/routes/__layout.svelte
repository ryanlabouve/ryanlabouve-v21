<script lang="ts">
	import Header from '$lib/header/Header.svelte';
	import '../app.css';

	async function submitForm() {
		alert("I haven't done this yet! DM me on twitter @ryanlabouve and I'll send you a dollar.");
	}
</script>

<div class="dark:bg-gray-900 dark:text-gray-200 flex flex-col" style="min-height: 100vh;">
	<div>
		<Header />
	</div>

	<main class="flex-grow">
		<slot />
	</main>

	<div class="" style="">
		<footer class="dark:bg-gray-800" aria-labelledby="footer-heading">
			<div class="max-w-7xl mx-auto py-12 px-4 sm:px-6 lg:py-16 lg:px-8">
				<div
					class="border-t border-gray-200 pt-8 lg:flex lg:items-center lg:justify-between xl:mt-0"
				>
					<div>
						<h3 class="text-sm font-semibold text-gray-400 tracking-wider uppercase">
							Subscribe to my newsletter
						</h3>
						<p class="mt-2 text-base text-gray-500">
							Read about disasters recovery, web3, and shenanigans.
						</p>
					</div>
					<form
						class="mt-4 sm:flex sm:max-w-md lg:mt-0"
						on:submit|preventDefault={() => submitForm()}
					>
						<label for="email-address" class="sr-only">Email address</label>
						<input
							type="email"
							name="email-address"
							id="email-address"
							autocomplete="email"
							required=""
							class="appearance-none min-w-0 w-full bg-white border border-gray-300 py-2 px-4 text-base rounded-md text-gray-900 placeholder-gray-500 focus:outline-none focus:ring-indigo-500 focus:border-indigo-500 focus:placeholder-gray-400 sm:max-w-xs"
							placeholder="Enter your email"
						/>
						<div class="mt-3 rounded-md sm:mt-0 sm:ml-3 sm:flex-shrink-0">
							<button
								type="submit"
								class="w-full bg-indigo-600 border border-transparent rounded-md py-2 px-4 flex items-center justify-center text-base font-medium text-white hover:bg-indigo-700 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-indigo-500"
							>
								Subscribe
							</button>
						</div>
					</form>
				</div>
				<div class="mt-8 border-t border-gray-200 pt-8 md:flex md:items-center md:justify-between">
					<div class="flex space-x-6 md:order-2">
						<a href="#" class="text-gray-400 hover:text-gray-500">
							<svg class="h-6 w-6" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true">
								<path
									d="M8.29 20.251c7.547 0 11.675-6.253 11.675-11.675 0-.178 0-.355-.012-.53A8.348 8.348 0 0022 5.92a8.19 8.19 0 01-2.357.646 4.118 4.118 0 001.804-2.27 8.224 8.224 0 01-2.605.996 4.107 4.107 0 00-6.993 3.743 11.65 11.65 0 01-8.457-4.287 4.106 4.106 0 001.27 5.477A4.072 4.072 0 012.8 9.713v.052a4.105 4.105 0 003.292 4.022 4.095 4.095 0 01-1.853.07 4.108 4.108 0 003.834 2.85A8.233 8.233 0 012 18.407a11.616 11.616 0 006.29 1.84"
								/>
							</svg>
						</a>

						<a href="#" class="text-gray-400 hover:text-gray-500">
							<svg class="h-6 w-6" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true">
								<path
									fill-rule="evenodd"
									d="M12 2C6.477 2 2 6.484 2 12.017c0 4.425 2.865 8.18 6.839 9.504.5.092.682-.217.682-.483 0-.237-.008-.868-.013-1.703-2.782.605-3.369-1.343-3.369-1.343-.454-1.158-1.11-1.466-1.11-1.466-.908-.62.069-.608.069-.608 1.003.07 1.531 1.032 1.531 1.032.892 1.53 2.341 1.088 2.91.832.092-.647.35-1.088.636-1.338-2.22-.253-4.555-1.113-4.555-4.951 0-1.093.39-1.988 1.029-2.688-.103-.253-.446-1.272.098-2.65 0 0 .84-.27 2.75 1.026A9.564 9.564 0 0112 6.844c.85.004 1.705.115 2.504.337 1.909-1.296 2.747-1.027 2.747-1.027.546 1.379.202 2.398.1 2.651.64.7 1.028 1.595 1.028 2.688 0 3.848-2.339 4.695-4.566 4.943.359.309.678.92.678 1.855 0 1.338-.012 2.419-.012 2.747 0 .268.18.58.688.482A10.019 10.019 0 0022 12.017C22 6.484 17.522 2 12 2z"
									clip-rule="evenodd"
								/>
							</svg>
						</a>

						<a href="#" class="text-gray-400 hover:text-gray-500">
							<svg
								role="img"
								class="icon h-6 w-6"
								fill="currentColor"
								viewBox="0 0 24 24"
								xmlns="http://www.w3.org/2000/svg"
								><title>LinkedIn</title><path
									d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433c-1.144 0-2.063-.926-2.063-2.065 0-1.138.92-2.063 2.063-2.063 1.14 0 2.064.925 2.064 2.063 0 1.139-.925 2.065-2.064 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"
								/></svg
							>
						</a>
					</div>
					<p class="mt-8 text-base text-gray-400 md:mt-0 md:order-1">
						© 2020 too RyanLaBouve. Most rights reserved.
					</p>
				</div>
			</div>
		</footer>
	</div>
</div>
