<script>
  export let placeholder = [
  {imgSrc: ''},
  {imgAlt: ''},
  {heading: ''}
]

</script>

<div class="p-4 m-4 flex flex-col w-[30%] h-[250px] justify-center bg-secondary-300 items-center">
  <img class="flex-none w-[100px] h-[100px] fill-white stroke-white " src={placeholder.imgSrc} alt={placeholder.imgAlt}>
  <h5 class="text-surface-900 justify-self-center text-xl font-bold mt-4">{placeholder.heading}</h5>
</div>