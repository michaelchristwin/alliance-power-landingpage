<script lang="ts">
	import hero_img from '$lib/assets/solar-hero.webp';
	import zamfara from '$lib/assets/partners/Zamfara-Government.webp';
	import taj from '$lib/assets/partners/Taj-Bank.webp';
	import crown_club from '$lib/assets/partners/Crown-Ranch-logo.webp';
	import glisten from '$lib/assets/partners/Glisten-logo-full.webp';
	import jaiz from '$lib/assets/partners/Jaiz-Bank-logo.webp';
</script>

<svelte:head>
	<title>Alliance Power Generation</title>
	<meta
		name="description"
		content="Projects Completed In Last 3 Years 1 Happy Clients Who Trust Us 10 With a strong focus on research and development, Alliance Power Generation Company has developed cutting-edge solar technologies and solutions that maximize energy production and optimize energy efficiency. Our team..."
	/>
	<meta property="og_title" content="Alliance Power Generation" />
	<meta
		property="og_description"
		content="Projects Completed In Last 3 Years 1 Happy ClientsWho Trust Us 10 With a strong focus on research and development, Alliance Power Generation Company has developed cutting-edge solar technologies and solutions that maximize energy production and optimize energy efficiency. Our team..."
	/>
</svelte:head>
<main class="inter h-screen w-screen overflow-x-hidden overflow-y-auto scroll-smooth p-20">
	<div class="flex h-[70vh] w-full items-center justify-between bg-cover bg-center">
		<div class="h-fit w-150 items-center">
			<h1 class="text-[50px] leading-relaxed font-bold text-black">
				Power Your Business with Clean, Reliable Energy
			</h1>
			<p class="text-xl leading-normal text-neutral-500">
				Scalable renewable generation solutions that cut costs, reduce risk, and future-proof your
				operations.
			</p>
			<button
				type="button"
				class="mt-5 h-14 w-50 rounded-4xl border bg-[#03a9f4] text-white hover:bg-[#03a9f4]/80"
				>Get Quote</button
			>
		</div>
		<img src={hero_img} alt="Hero" class="h-125 w-125 rounded-full object-cover object-center" />
	</div>
	<div class="mt-40 h-140 w-full">
		<h2 class="text-center text-3xl font-semibold">Our Partners</h2>
		<div class="mt-10 grid grid-cols-2 place-items-center md:grid-cols-3 lg:grid-cols-5">
			<img src={taj} alt="Taj Bank" class="h-50 w-50 rounded-full object-contain object-center" />
			<img src={jaiz} alt="Jaiz Bank" class="h-50 w-50 rounded-full object-contain object-center" />
			<img
				src={zamfara}
				alt="Zamfara state government Nigeria"
				class="h-50 w-50 rounded-full object-contain object-center"
			/>
			<img src={crown_club} alt="Crown club and resorts" class="h-50 w-50 rounded-full" />
			<img
				src={glisten}
				alt="Glisten international academy"
				class="h-50 w-50 rounded-full object-contain object-center"
			/>
		</div>
	</div>
	<section class="bg-gray-50 py-16">
		<div class="mx-auto max-w-7xl px-4 text-center sm:px-6 lg:px-8">
			<h2 class="mb-4 text-3xl font-extrabold text-gray-900">Power. Efficiency. Sustainability.</h2>
			<p class="mb-12 text-gray-600">
				Complete solar solutions that reduce costs, drive sustainability, and put you first.
			</p>

			<div class="grid gap-8 sm:grid-cols-1 md:grid-cols-3">
				<!-- Card 1 -->
				<div
					class="flex flex-col items-center rounded-xl bg-white p-6 text-center shadow-md transition hover:shadow-xl"
				>
					<div class="mb-4 rounded-full bg-yellow-100 p-4">
						<!-- Example icon: solar panel -->
						<svg
							xmlns="http://www.w3.org/2000/svg"
							width="24"
							height="24"
							viewBox="0 0 24 24"
							fill="none"
							stroke="oklch(79.5% 0.184 86.047)"
							stroke-width="2"
							stroke-linecap="round"
							stroke-linejoin="round"
							class="lucide lucide-sun-icon lucide-sun"
							><circle cx="12" cy="12" r="4" /><path d="M12 2v2" /><path d="M12 20v2" /><path
								d="m4.93 4.93 1.41 1.41"
							/><path d="m17.66 17.66 1.41 1.41" /><path d="M2 12h2" /><path d="M20 12h2" /><path
								d="m6.34 17.66-1.41 1.41"
							/><path d="m19.07 4.93-1.41 1.41" /></svg
						>
					</div>
					<h3 class="mb-2 text-xl font-semibold">Complete Solar Solutions</h3>
					<p class="text-gray-600">
						Design, installation, maintenance, and energy consulting optimized for maximum ROI.
					</p>
				</div>

				<!-- Card 2 -->
				<div
					class="flex flex-col items-center rounded-xl bg-white p-6 text-center shadow-md transition hover:shadow-xl"
				>
					<div class="mb-4 rounded-full bg-green-100 p-4">
						<!-- Example icon: leaf -->
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
							class="lucide lucide-leaf-icon lucide-leaf text-green-500"
							><path
								d="M11 20A7 7 0 0 1 9.8 6.1C15.5 5 17 4.48 19 2c1 2 2 4.18 2 8 0 5.5-4.78 10-10 10Z"
							/><path d="M2 21c0-3 1.85-5.36 5.08-6C9.5 14.52 12 13 13 12" /></svg
						>
					</div>
					<h3 class="mb-2 text-xl font-semibold">Lower Costs, Greener Future</h3>
					<p class="text-gray-600">
						Cut energy bills, reduce reliance on traditional power, and contribute to a cleaner
						planet.
					</p>
				</div>

				<!-- Card 3 -->
				<div
					class="flex flex-col items-center rounded-xl bg-white p-6 text-center shadow-md transition hover:shadow-xl"
				>
					<div class="mb-4 rounded-full bg-blue-100 p-4">
						<!-- Example icon: support -->
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
							class="lucide lucide-headset-icon lucide-headset text-blue-500"
							><path
								d="M3 11h3a2 2 0 0 1 2 2v3a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-5Zm0 0a9 9 0 1 1 18 0m0 0v5a2 2 0 0 1-2 2h-1a2 2 0 0 1-2-2v-3a2 2 0 0 1 2-2h3Z"
							/><path d="M21 16v2a4 4 0 0 1-4 4h-5" /></svg
						>
					</div>
					<h3 class="mb-2 text-xl font-semibold">Seamless Customer Experience</h3>
					<p class="text-gray-600">
						Expert guidance and support at every step to ensure a smooth, worry-free journey.
					</p>
				</div>
			</div>

			<!-- CTA -->
			<div class="mt-12">
				<a
					href="/"
					class="inline-block rounded-4xl bg-[#03a9f4] px-8 py-3 font-semibold text-white shadow-md transition hover:bg-[#03a9f4]/80"
				>
					Get Started
				</a>
			</div>
		</div>
	</section>
</main>

<style lang="postcss">
	@reference "tailwindcss";
</style>
