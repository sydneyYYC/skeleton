<script>
	import '../app.postcss';
	 let navLinks = [
		{title: "home", href:"/"},
		{title: "The Orange", href:"/TheOrange"},
		{title: "I peeled my orange today", href:"/Ipeeledmyorange"}
	]
	let title;
	import { LightSwitch } from '@skeletonlabs/skeleton';
	import Footer from "../lib/Footer.svelte";
	import { AppShell } from "@skeletonlabs/skeleton";
	import { AppBar } from '@skeletonlabs/skeleton';
</script>

<div class="min-w-full flex justify-between card-header items-center">
	<div class="placeholder-circle w-10 mb-4 btn-icon variant-filled-surface hover:variant-filled-secondary"/>
	<ul class="flex justify-around min-w-[50%]">
	{#each navLinks as {href, title}}
	<li class="btn variant-filled-surface hover:variant-filled-secondary"><a {href}>{title}</a></li>
	{/each}
</ul>
<LightSwitch />
</div>


	<AppShell>
		<AppBar>
			<svelte:fragment slot="headline"> <h2 class="text-5xl text-center">{title}</h2></svelte:fragment>
		</AppBar>
	
		<slot />

		<svelte:fragment slot="pageFooter"><Footer/></svelte:fragment>
		<!-- (footer) -->
	</AppShell>
	

