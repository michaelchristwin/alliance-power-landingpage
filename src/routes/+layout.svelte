<script lang="ts">
	import './layout.css';
	import favicon from '$lib/assets/favicon.svg';

	let { children } = $props();
</script>

<svelte:head><link rel="icon" href={favicon} /></svelte:head>
<header
	class="sticky top-0 z-20 flex h-12.5 w-full items-center justify-between bg-[#3f3e73] px-20 text-white"
>
	<h1 class="text-[16px] font-bold md:text-lg">ALLIANCE POWER</h1>
	<nav>
		<ul class="flex h-full items-center justify-around space-x-4 text-sm font-bold md:text-[16px]">
			<li>ABOUT</li>
			<li>CAREERS</li>
			<li>PROJECTS</li>
			<li>CONTACT US</li>
		</ul>
	</nav>
</header>
{@render children()}
