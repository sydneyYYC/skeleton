<script>
	import { AppBar, AppShell, LightSwitch } from "@skeletonlabs/skeleton";
	
  let title = "About Us"
</script>

<AppBar><svelte:fragment slot="headline"> <h2 class="text-5xl text-center justify-center">{title}</h2></svelte:fragment></AppBar>
<main >
	<div class="grid grid-cols-3 grid-rows-2">
	<img src='./assets/03-placeholder.jpg' alt="mountain" class="col-span-full col-start-1 row-start-1 row-span-full w-screen h-[600px]">
	<div class=" max-h-[60%] z-10 bg-secondary-100 col-start-2 row-start-2  row-span-full text-surface-700 self-end p-4 overflow-hidden">
	<h3 class="text-2xl pb-2">My Big Heading</h3>
	<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Consequuntur cum cupiditate aperiam et natus ullam quo inventore, mollitia a sapiente.</p>
	</div>
	</div>
	<section class="flex bg-surface-800">
		<div class="p-4 m-4 flex flex-col w-[30%] h-[250px] justify-center bg-tertiary-300 items-center">
			<h5 class="text-surface-900 justify-self-center text-2xl font-bold my-4">Section One</h5>
      <p class="max-w-[20ch] text-lg text-surface-800 justify-self-center">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Expedita, temporibus?</p>
		</div>

		<div class="p-4 m-4 flex flex-col w-[30%] h-[250px] justify-center bg-tertiary-300 items-center">
			<h5 class="text-surface-900 justify-self-center text-2xl font-bold my-4">Section Two</h5>
      <p class="max-w-[20ch] text-lg text-surface-800 justify-self-center">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Expedita, temporibus?</p>
		</div>

		<div class="p-4 m-4 flex flex-col w-[30%] h-[250px] justify-center bg-tertiary-300 items-center">
			<h5 class="text-surface-900 justify-self-center text-2xl font-bold my-4">Section Three</h5>
      <p class="max-w-[20ch] text-lg text-surface-800 justify-self-center">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Expedita, temporibus?</p>
		</div>
	</section>
	<section class="flex flex-col justify-center items-center p-6 min-w-full bg-surface-700">
		<h3 class="text-2xl font-bold text-tertiary-200 m-4">More Info</h3>
		<p class="max-w-prose m-4">Lorem ipsum dolor sit amet consectetur adipisicing elit. Iusto repudiandae, earum ullam dolores cum dolorem. Culpa eveniet dolor provident eos. Alias aperiam laudantium molestiae aliquid. Quam officiis nostrum sapiente odio iure provident voluptate, ullam labore cumque reiciendis excepturi dolorum exercitationem!</p>
	</section>
</main>
