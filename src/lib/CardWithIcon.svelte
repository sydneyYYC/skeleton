<script>
//   export let placeholder = [
//   {imgSrc: ''},
//   {imgAlt: ''},
//   {heading: ''}
// ]

export let imgSrc = "./assets/02-logo.svg";
export let imgAlt = "placeholder";
export let heading = "subheading";

</script>

<div class="p-4 m-4 flex flex-col w-[30%] h-[250px] justify-center bg-secondary-300 items-center">
  <img class="flex-none w-[100px] h-[100px] fill-white stroke-white " src={imgSrc} alt={imgAlt}>
  <h5 class="text-surface-900 justify-self-center text-xl font-bold mt-4">{heading}</h5>
</div>