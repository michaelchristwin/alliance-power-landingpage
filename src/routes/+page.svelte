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
							class="h-8 w-8 text-yellow-500"
							fill="none"
							viewBox="0 0 24 24"
							stroke="currentColor"
						>
							<path
								stroke-linecap="round"
								stroke-linejoin="round"
								stroke-width="2"
								d="M12 3v18m9-9H3"
							/>
						</svg>
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
							class="h-8 w-8 text-green-500"
							fill="none"
							viewBox="0 0 24 24"
							stroke="currentColor"
						>
							<path
								stroke-linecap="round"
								stroke-linejoin="round"
								stroke-width="2"
								d="M12 3C7 7 5 13 5 19h14c0-6-2-12-7-16z"
							/>
						</svg>
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
							class="h-8 w-8 text-blue-500"
							fill="none"
							viewBox="0 0 24 24"
							stroke="currentColor"
						>
							<path
								stroke-linecap="round"
								stroke-linejoin="round"
								stroke-width="2"
								d="M18 8a6 6 0 01-12 0M12 12v9"
							/>
						</svg>
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
					href="#contact"
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
