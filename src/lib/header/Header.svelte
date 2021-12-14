<script lang="ts">
	import { page } from '$app/stores';
</script>

<header>
	<nav>
		<ul>
			<li class:active={$page.path === '/'}><a sveltekit:prefetch href="/">Home</a></li>
			<li class:active={$page.path === '/about'}><a sveltekit:prefetch href="/about">About</a></li>
			<li class:active={$page.path === '/todos'}><a sveltekit:prefetch href="/todos">Todos</a></li>
		</ul>
		<ul>
			<li>https://twitter.com/ryanlabouve</li>
			<li>https://github.com/ryanlabouve</li>
			<li>https://www.linkedin.com/in/ryanlabouve/</li>
		</ul>
	</nav>
</header>
