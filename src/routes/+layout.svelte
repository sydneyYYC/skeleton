<script>
	import '../app.postcss';
	import { AppBar } from '@skeletonlabs/skeleton';
	export let title = 'Hello :)';
	 let navLinks = [
		{title: "home", href:"/"},
		{title: "about", href:"/About"},
		{title: "contact", href:"/Contact"}
	]
</script>

<div class="min-w-full flex justify-between">
	<div class="placeholder-circle w-10 m-2" />
	<ul class="flex justify-around min-w-[50%] justify-self-end self-center p-2 hover:">
	{#each navLinks as {href, title}}
	<li><a {href}>{title}</a></li>
	{/each}
</ul>
</div>

<AppBar>
<svelte:fragment slot="headline"> <h2 class="text-5xl text-center">{title}</h2></svelte:fragment>
</AppBar>
<slot />
