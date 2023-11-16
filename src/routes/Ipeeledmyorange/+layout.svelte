<script>
import { ListBox, ListBoxItem } from '@skeletonlabs/skeleton';
let boxItem = [
	{name:"Books", value:"books", valuesingle: "books"},
	{name:"Movies", value:"movies", valuesingle: "movies"},
	{name: 'TV', value:"tv", valuesingle: "movies"},
	{name: 'more', value:"more", valuesingle: "more"},
	{name: 'stuff', value:"stuff", valuesingle: "stuff"},
	{name: 'here', value:"here", valuesingle: "here"}
]
</script>

<main class="m-4 flex ">
	<div>
		<div class="max-w-max bg-tertiary-800 p-4 rounded-lg m-4 self-center min-h-screen">
			<ListBox>
				{#each boxItem as {name, value, valueSingle}}
				<ListBoxItem bind:group={valueSingle} name="medium" value={value}>{name}</ListBoxItem>
				{/each}
			</ListBox>
		</div>
</div>
	<div>
		<slot />
	</div>

</main>


