<script>
	import '../app.postcss';
	 let navLinks = [
		{title: "home", href:"/"},
		{title: "About Us", href:"/TheOrange"},
		{title: "Our Products", href:"/Ipeeledmyorange"}
	]
	
	
	import Footer from "../lib/Footer.svelte";
	import { AppShell, AppBar } from "@skeletonlabs/skeleton";
</script>

<!-- Nav Bar -->
<div class="min-w-full flex justify-between card-header items-center my-4">
	<div class="placeholder-circle w-10 btn-icon variant-ghost-secondary hover:variant-filled-secondary" />
	
	<ul class="flex justify-around min-w-[50%] mb-4">
	{#each navLinks as {href, title}}
	<li class="btn variant-ghost-secondary hover:variant-filled-secondary"><a {href}>{title}</a></li>
	{/each}
</ul>
</div>

	<!-- main page -->
	<AppShell>
		<!-- header section -->
		<AppBar>
			
		</AppBar>
	
		<slot />
		<!-- footer -->
		<svelte:fragment slot="pageFooter"><Footer/></svelte:fragment>
		<!-- (footer) -->
	</AppShell>
	

