<script>
  let cardItems = [
    {heading: "product 1", src:"./assets/cards/01-cardimg.jpg", alt: "yellow backpack"},
    {heading: "product 2", src:"./assets/cards/02-cardimg.jpg", alt: "many backpacks"},
    {heading: "product 3", src:"./assets/cards/03-cardimg.jpg", alt: "cup"},
    {heading: "product 4", src:"./assets/cards/04-cardimg.jpg", alt: "yellow gloves"},
    {heading: "product 5", src:"./assets/cards/05-cardimg.jpg", alt: "table in water"},
    {heading: "product 6", src:"./assets/cards/06-cardimg.jpg", alt: "sleeping bag"}
  ]
</script>

<h4 class="text-2xl mr-8 text-center">OUR PRODUCTS</h4>
<div class=" ml-8 text-center flex g-2 flex-wrap m">
  {#each cardItems as {heading, src, alt}}
<a href="/" class="card m-2"> <div class=" card max-w-max p-4 w-[500px]"><img class="w-[300px] h-auto "src="{src}" alt="{alt}">{heading}</div></a>
  {/each}
</div>