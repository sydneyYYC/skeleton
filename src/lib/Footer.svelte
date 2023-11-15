<script>
  export let footerLinks = [
		{title: "home", href:"/"},
		{title: "about", href:"/About"},
		{title: "contact", href:"/Contact"}
]
</script>

<footer class="card-footer min-w-full m-0">
  <div class="bg-primary-500">
    <ul>
      {#each footerLinks as {href, title}}
      <li><a {href}>{title}</a></li>
      {/each}
    </ul>
  </div>
</footer>