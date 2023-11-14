<script>
	import '../app.postcss';
	 let navLinks = [
		{title: "home", href:"/"},
		{title: "about", href:"/About"},
		{title: "contact", href:"/Contact"}
	]
</script>

<div class="min-w-full flex justify-between card-header items-center ">
	<div class="placeholder-circle w-10 mb-4 btn-icon variant-filled-surface hover:variant-filled-secondary"/>
	<ul class="flex justify-around min-w-[50%]">
	{#each navLinks as {href, title}}
	<li class="btn variant-filled-surface hover:variant-filled-secondary"><a {href}>{title}</a></li>
	{/each}
</ul>
</div>


<slot />
