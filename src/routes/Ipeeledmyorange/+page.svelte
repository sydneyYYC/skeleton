<script>
  let cardItems = [
    {heading: "product 1", src:"./assets/cards/01-cardimg.jpg", alt: "yellow backpack"}
  ]
</script>
<div class="mx-2 text-center">
  {#each cardItems as {heading, src, alt}}
<a href="/" class="card"> <div class=" card max-w-max p-4"><img class="w-[200px] h-auto "src="{src}" alt="{alt}">{heading}</div></a>
  {/each}
</div>