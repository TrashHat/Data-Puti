<script>
	import { Accordion, AccordionItem, Avatar } from '@skeletonlabs/skeleton';
</script>

<!-- Home -->
<div class="border-black border-b-2">
	<article id="Home" class="wrapper style1">
		<section>
	<div class="px-4 mx-auto max-w-screen-xl text-center py-60">
		<h1
			class="mb-4 text-4xl tracking-tight leading-none text-black md:text-5xl lg:text-6xl"
		>
		What is a <u>Filipino's</u> worth to their <u>oppressors</u>?
		</h1>
		<br>
		<div class="container mx-auto px-4">
			<p class="mb-8 text-lg font-normal text-gray-900 lg:text-xl sm:px-16 lg:px-48 text-justify">
				Our project aims to identify the interconnectedness between series of political unrest from 2016 to present day. Particularly, our project aims to identify patterns between these events and act as a medium for future researchers aiming to understand the political status of the country and formulate means or methods to improve the country’s current conditions.
			</p>
		</div>
	</div>
</section>


	</article>
</div>

<br>

<!-- Overview -->
<div class="border-black border-b-2 py-5">
	<div class="container p-10 mx-auto">
		<article id="Overview" class="wrapper style2">
			<section>
				<h1 class="mb-4 text-4xl tracking-tight leading-none text-black md:text-5xl lg:text-4xl dark:text-white">Here's an overview of our project.</h1>
			</section>

			<Accordion >
				<AccordionItem open class="border-black border-b-2">
					<svelte:fragment slot="lead"></svelte:fragment>
					<svelte:fragment slot="summary"><h2 class="mb-4 text-xl tracking-tight leading-none text-black md:text-2xl lg:text-3xl dark:text-white">Background</h2></svelte:fragment>
					<svelte:fragment slot="content">In 2021, Freedom House reported a significantly low scores in political rights and civil liberties for the Philippines. This came after the Duterte administration failed to secure peace treaties with the CPP-NPA and more, declared them as terrorists. Journalists, activities, and opposing political parties also became main targets of harassment and were labelled as communist sympathizers which resulted in increased risks of physical assault from state forces. Furthermore, the administration forced the closure of Islamic and Indigenous schools and the illegal arrests of their students due to allegations as possible recruitment sites for militants. These are among the previous administration's tactics to subvert insurgency which worsened civil conflicts and allowed them to persist until the current administration.
						<p>References: 
							<a href="https://freedomhouse.org/country/philippines/freedom-world/2021#PR">[1]</a>
							<a href="https://www.rappler.com/moveph/lumad-schools-continue-to-suffer-closures-attacks-coronavirus-pandemic/">[2]</a>
						</p>
					</svelte:fragment>
				</AccordionItem>
				<AccordionItem class="border-black border-b-2">
					<svelte:fragment slot="lead"></svelte:fragment>
					<svelte:fragment slot="summary">
						<h2 class="mb-4 text-xl tracking-tight leading-none text-black md:text-2xl lg:text-3xl dark:text-white">
							Research Questions
						</h2>
					</svelte:fragment>
					<svelte:fragment slot="content">
						<p class="dark:text-white">1. How interconnected (in terms of geographical and temporal proximity, conflicting sides, cause, etc.) are the conflicts that have occurred since the Duterte administration?</p>
						<p class="dark:text-white">2. Do conflicts in the Philippines show patterns (e.g. certain times of the year) on when they are more likely to occur?</p>
					</svelte:fragment>
				</AccordionItem>
				<AccordionItem class="border-black border-b-2">
					<svelte:fragment slot="lead"></svelte:fragment>
					<svelte:fragment slot="summary">
						<h2 class="mb-4 text-xl tracking-tight leading-none text-black md:text-2xl lg:text-3xl dark:text-white">
							Plan of Action
						</h2>
					</svelte:fragment>
					<svelte:fragment slot="content">
						<p class="dark:text-white">Our approach uses Data Science to analyze and visualize the factors of interconnection (location, date of occurrence, actors, types of event) of the conflicts since the Duterte administration, as well as examine the timestamps and frequency of these incidents to identify the trends in their occurrence.</p>
					</svelte:fragment>
				</AccordionItem>
				<AccordionItem class="border-black border-b-2">
					<svelte:fragment slot="lead"></svelte:fragment>
					<svelte:fragment slot="summary">
						<h2 class="mb-4 text-xl tracking-tight leading-none text-black md:text-2xl lg:text-3xl dark:text-white">
							Null Hypotheses
						</h2>
					</svelte:fragment>
					<svelte:fragment slot="content">
						<p class="dark:text-white">The sociopolitical conflicts in the Philippines occur randomly.</p>
					</svelte:fragment>
				</AccordionItem>
				<AccordionItem class="border-black border-b-2">
					<svelte:fragment slot="lead"></svelte:fragment>
					<svelte:fragment slot="summary">
						<h2 class="mb-4 text-xl tracking-tight leading-none text-black md:text-2xl lg:text-3xl dark:text-white">
							Alternative Hypotheses
						</h2>
					</svelte:fragment>
					<svelte:fragment slot="content">
						<p class="dark:text-white">The sociopolitical conflicts in the Philippines occur under geographical and historical context.</p>
					</svelte:fragment>
				</AccordionItem>
			</Accordion>
		</article>
	</div>
</div>

<!-- Data -->
<div class="border-black border-b-2 py-10">
	<div class="container p-10 mx-auto flex flex-col items-center">
		<section>
			<h1 class="mb-4 text-4xl tracking-tight leading-none text-black md:text-5xl lg:text-4xl dark:text-white">Our Dataset</h1>
		</section>
		<article id="#Data" class="wrapper style3">
			<div class="btn-group variant-ghost-secondary [&>*+*]:border-secodary-500 ">
				<button><a href="https://docs.google.com/document/d/1w8oLWkDG3S4PgmrsU2fRgTXZqCG8nchQ5YBVCGPhkgY/edit?usp=sharing" class="button large scrolly">Guide to the Data Set</a></button>
				<button><a href="https://docs.google.com/spreadsheets/d/1h00TUat9JPPCv1T8tWFzQ_t_ZR2ZovRk/edit?usp=drive_link&ouid=108314072179584311538&rtpof=true&sd=true" class="button large scrolly">Data Set</a></button>
			</div>
		</article>
	</div>
</div>

<!-- Exploration -->
<div class="border-black border-b-2 py-10">
	<article id="#Exploration" class="wrapper style2">
		
	</article>
</div>

<br>

<!-- Findings -->
<div class="border-black border-b-2 py-10">
	<article id="#Findings" class="wrapper style2"></article>
</div>


<br>

<!-- Team -->
<div class="container p-10 mx-auto ">
	<article id="#Team" class="wrapper style2">
	<div class="flex gap-5 space-x-4 justify-center">
		<div class="card card-hover p-4 flex flex-col items-center">
			<a href="https://github.com/davidandal"> 
				<Avatar src="https://pngimg.com/uploads/github/github_PNG40.png" width="w-32" rounded="rounded-full" />
			</a>
			<h2 class="font-bold">David Vincent C. Andal, WFZ</h2>
			<br>
			<p>Hallo! I'm David, currently in my second year, taking up BS Computer Science at the University of the Philippines - Diliman. My dream is to become a game developer, using Data Science to enhance gameplay and create unforgettable experiences for future players. You'll find me working on small game projects or playing online games.
			</p>
		</div>
		<div class="card card-hover p-4 flex flex-col items-center">
			<a href="https://github.com/TrashHat"> 
				<Avatar src="https://pngimg.com/uploads/github/github_PNG40.png" width="w-32" rounded="rounded-full" />
			</a>
			<h2 class="font-bold">Julian Andrei C. Dolojan, WFZ</h2>
			<br>
			<p></p>
		</div>
		<div class="card card-hover p-4 flex flex-col items-center">
			<a href="https://github.com/justinelsrn"> 
				<Avatar src="https://pngimg.com/uploads/github/github_PNG40.png" width="w-32" rounded="rounded-full" />
			</a>
			<h2 class="font-bold">Justine Eusebio Soriano, WFZ</h2>
			<br>
			<p>Hiii, I'm Seb, a Sophomore (actually, third-year) Computer Science undergrad from the University of the Philippines - Diliman. I hope to contribute to medical diagnostics some time in the future. Outside acads, I enjoy slice-of-life lighthearted dramas and reading, sometimes writing, poetry!
			</p>
		</div>
	</div>
	</article>
</div>

<br>

<!-- bg-secondary-300 dark:bg-slate-800 -->
<!-- block card card-hover -->