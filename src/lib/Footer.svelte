<script>
  export let footerLinks = [
		{title: "home", href:"/"},
		{title: "about", href:"/About"},
		{title: "contact", href:"/Contact"}
]
</script>

<footer class="min-w-full m-0 self-end flex justify-between bg-secondary-900">
  <div class="bg-secondary-900 flex flex-col p-4 mx-4">
    <p class="self-start text-xl">Links</p>
    <ul class="">
      {#each footerLinks as {href, title}}
      <li><a {href}>{title}</a></li>
      {/each}
    </ul>
    <p class="mt-4 ">&copy;Sydney Bruce</p>
  </div>
</footer>