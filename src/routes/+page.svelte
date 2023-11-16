
<script>
	import Footer from "../lib/Footer.svelte";
	import { AppShell } from "@skeletonlabs/skeleton";
	import { AppBar } from '@skeletonlabs/skeleton';
	let title = 'HOME';
</script>

<AppBar><svelte:fragment slot="headline"> <h2 class="text-5xl text-center justify-center">{title}</h2></svelte:fragment></AppBar>
<main >
	<div class="grid grid-cols-3 grid-rows-2">
	<img src='./assets/02-placeholder.jpg' alt="leaf" class="col-span-full col-start-1 row-start-1 row-span-full w-screen h-[600px]">
	<div class=" max-h-[60%] z-10 bg-secondary-100 col-start-2 row-start-2  row-span-full text-surface-700 self-end p-4 overflow-hidden">
	<h3 class="text-2xl pb-2">My Big Heading</h3>
	<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Consequuntur cum cupiditate aperiam et natus ullam quo inventore, mollitia a sapiente.</p>
	</div>
	</div>
	<section class="flex g-2">
		<div class="p-4 m-4 flex flex-col w-[30%] h-[250px] justify-center bg-secondary-700 items-center">
			<img class="flex-none w-[100px] h-[100px] fill-white stroke-white " src="./assets/04-logo.svg" alt = "logo placeholder items-center p-2">
			<h5 class="text-white justify-self-center text-lg mt-4">Heading 4</h5>
		</div>

		<div class="p-4 m-4 flex flex-col  w-[30%] justify-center bg-secondary-700 items-center">
			<img class="flex-none w-[100px] h-[100px] fill-white stroke-white p-2" src="./assets/03-logo.svg" alt = "logo placeholder">
			<h5 class="text-white justify-self-center text-lg mt-4">Heading 4</h5>
		</div>

		<div class="p-4 m-4 flex flex-col  w-[30%] justify-center bg-secondary-700 items-center">
			<img class="flex-none w-[100px] h-[100px] fill-white stroke-white p-2" src="./assets/01-logo.svg" alt = "logo placeholder">
			<h5 class="text-white justify-self-center text-lg mt-4">Heading 4</h5>
		</div>
	</section>
</main>

	
