<script>
import { ListBox, ListBoxItem } from '@skeletonlabs/skeleton';
let boxItem = [
	{name:"Books", value:"books", valuesingle: "books"},
	{name:"Movies", value:"movies", valuesingle: "movies"},
	{name: 'TV', value:"tv", valuesingle: "movies"}
]
</script>

<main class="m-4">
	<h4 class="text-2xl mr-8 text-center">OUR PRODUCTS</h4>
	<div class="max-w-max bg-tertiary-800 p-4 rounded-lg m-4">
	<ListBox>
		{#each boxItem as {name, value, valueSingle}}
		<ListBoxItem bind:group={valueSingle} name="medium" value={value}>{name}</ListBoxItem>
		{/each}
	</ListBox>
	</div>


	<slot />

</main>


