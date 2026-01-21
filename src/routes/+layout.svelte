<script lang="ts">
	import './layout.css';
	import favicon from '$lib/assets/favicon.svg';

	let { children } = $props();
	let open = $state(false);
</script>

<svelte:head><link rel="icon" href={favicon} /></svelte:head>
<header
	class="sticky top-0 z-20 flex h-12.5 w-full items-center justify-between bg-[#3f3e73] px-10 text-white md:px-20"
>
	<h1 class="text-sm font-bold md:text-lg">ALLIANCE POWER</h1>
	<nav>
		<ul
			class="hidden h-full items-center justify-around space-x-2 text-sm font-bold md:flex md:space-x-4 md:text-[16px]"
		>
			<li>ABOUT</li>
			<li>CAREERS</li>
			<li>PROJECTS</li>
			<li>CONTACT US</li>
		</ul>
	</nav>
	<button
		type="button"
		aria-label="Open Menu"
		class="block md:hidden"
		onclick={() => (open = !open)}
	>
		<svg
			xmlns="http://www.w3.org/2000/svg"
			width="24"
			height="24"
			viewBox="0 0 24 24"
			fill="none"
			stroke="currentColor"
			stroke-width="2"
			stroke-linecap="round"
			stroke-linejoin="round"
			class="lucide lucide-menu-icon lucide-menu"
			><path d="M4 5h16" /><path d="M4 12h16" /><path d="M4 19h16" /></svg
		>
	</button>
	{#if open}
		<nav class="absolute top-full left-0 z-50 w-full bg-white text-black shadow-md md:hidden">
			<ul class="flex flex-col gap-4 p-6 font-bold">
				<li><a href="/about">About</a></li>
				<li><a href="/projects">Projects</a></li>
				<li><a href="/contact">Contact</a></li>
			</ul>
		</nav>
	{/if}
</header>

{@render children()}
