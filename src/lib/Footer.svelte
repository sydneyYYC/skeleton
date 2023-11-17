<script>
  export let footerLinks = [
		{title: "home", href:"/"},
		{title: "about", href:"/About"},
		{title: "contact", href:"/Contact"}
]
</script>

<footer class="min-w-full m-0 self-end flex justify-between bg-surface-800">
  <div class=" flex flex-col p-4 mx-4 self-center justify-self-center">
    <p class="self-start text-xl px-2">Links</p>
    <ul class="max-w-max">
      {#each footerLinks as {href, title}}
      <li class="hover:variant-ghost-secondary rounded-full p-2"><a {href}>{title}</a></li>
      {/each}
    </ul>
    <p class="mt-4 ">&copy;Sydney Bruce</p>
  </div>
</footer>