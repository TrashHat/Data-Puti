<script lang ="ts">
	import '../app.postcss';

	// Highlight JS
	import hljs from 'highlight.js/lib/core';
	import 'highlight.js/styles/github-dark.css';
	import { storeHighlightJs } from '@skeletonlabs/skeleton';
	import xml from 'highlight.js/lib/languages/xml'; // for HTML
	import css from 'highlight.js/lib/languages/css';
	import javascript from 'highlight.js/lib/languages/javascript';
	import typescript from 'highlight.js/lib/languages/typescript';

	hljs.registerLanguage('xml', xml); // for HTML
	hljs.registerLanguage('css', css);
	hljs.registerLanguage('javascript', javascript);
	hljs.registerLanguage('typescript', typescript);
	storeHighlightJs.set(hljs);

	import {AppShell, AppBar, LightSwitch} from '@skeletonlabs/skeleton';

</script>

<AppShell regionPage="relative" slotPageHeader="sticky top-0 z-10">
	<svelte:fragment slot="header">
		<AppBar slotDefault="place-self-center" slotTrail="place-content-end gap-4'" background="bg-error-900 dark:bg-zinc-900">
			<svelte:fragment slot="lead">
				<a href="#Home" class="text-white hover:ease-in duration-300 hover:opacity-50"><img src="/" alt="DataPuti"></a>
			</svelte:fragment>
			<nav class="gap-11">
				<a href="#Overview" class="text-white text-2xl hover:text-3xl hover:text-primary-500 hover:ease-in-out duration-300 hover:font-bold">Overview</a> <p class="text-white">|</p> 
				<a href="#Data" class="text-white text-2xl hover:text-3xl hover:text-primary-500 hover:ease-in-out duration-300 hover:font-bold">Data</a> <p class="text-white">|</p> 
				<a href="#Methods" class="text-white text-2xl hover:text-3xl hover:text-primary-500 hover:ease-in-out duration-300 hover:font-bold">Methods</a> <p class="text-white">|</p> 
				<a href="#Results" class="text-white text-2xl hover:text-3xl hover:text-primary-500 hover:ease-in-out duration-300 hover:font-bold">Results</a> <p class="text-white">|</p> 
				<a href="#Team" class="text-white text-2xl hover:text-3xl hover:text-primary-500 hover:ease-in-out duration-300 hover:font-bold">Team</a>
			</nav>
			<svelte:fragment slot="trail">
				<LightSwitch />
			</svelte:fragment>
		</AppBar>
	</svelte:fragment>
	<!-- (sidebarLeft) -->
	<!-- (sidebarRight) -->
	<!--(pageHeader)-->
	<!-- Router Slot -->
	<div class="container p-10 mx-auto">
		<slot />
	</div>
	<!-- ---- / ---- -->
	<svelte:fragment slot="pageFooter">
		<AppBar background="bg-error-900 dark:bg-zinc-900 text-white">
			<svelte:fragment slot="lead">
				<p></p>
			</svelte:fragment>
			<h6>
				Team DataPuti
			</h6>
		</AppBar>
	</svelte:fragment>
	<!-- (footer) -->
</AppShell>