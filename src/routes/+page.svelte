
<script>
	import Footer from "../lib/Footer.svelte";
	import { AppShell } from "@skeletonlabs/skeleton";
	import { AppBar } from '@skeletonlabs/skeleton';
	import CardWithIcon from "../lib/CardWithIcon.svelte";
	
	let title = 'HOME';

	let cardOne = [
		{imgSrc: "./assets/04-logo.svg"},
		{imgAlt: "logo placeholder" },
		{heading: "About Us"}
	];
</script>

<AppBar><svelte:fragment slot="headline"> <h2 class="text-5xl text-center justify-center">{title}</h2></svelte:fragment></AppBar>
<main >
	<!-- hero section -->
	<div class="grid grid-cols-3 grid-rows-2">
	<img src='./assets/02-placeholder.jpg' alt="leaf" class="col-span-full col-start-1 row-start-1 row-span-full w-screen h-[600px]">
	<div class=" max-h-[60%] z-10 bg-secondary-100 col-start-2 row-start-2  row-span-full text-surface-700 self-end p-4 overflow-hidden">
	<h3 class="text-2xl pb-2">My Big Heading</h3>
	<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Consequuntur cum cupiditate aperiam et natus ullam quo inventore, mollitia a sapiente.</p>
	</div>
	</div>
	<!-- cards section -->
	<section class="flex bg-surface-800">
		<div class="p-4 m-4 flex flex-col w-[30%] h-[250px] justify-center bg-secondary-300 items-center">
			<img class="flex-none w-[100px] h-[100px] fill-white stroke-white " src="./assets/04-logo.svg" alt = "logo placeholder">
			<h5 class="text-surface-900 justify-self-center text-xl font-bold mt-4">About Us</h5>
		</div>

		<div class="p-4 m-4 flex flex-col  w-[30%] justify-center bg-secondary-300 items-center">
			<img class="flex-none w-[100px] h-[100px] fill-white stroke-white p-2" src="./assets/03-logo.svg" alt = "logo placeholder">
			<h5 class="text-surface-900  justify-self-center text-lg mt-4">Our Products</h5>
		</div>

		<div class="p-4 m-4 flex flex-col  w-[30%] justify-center bg-secondary-300 items-center">
			<img class="flex-none w-[100px] h-[100px] fill-white stroke-white p-2" src="./assets/01-logo.svg" alt = "logo placeholder">
			<h5 class="text-surface-900  justify-self-center text-lg mt-4">Contact</h5>
		</div>
	</section>
	<section class="flex flex-col justify-center items-center p-6 min-w-full bg-surface-700">
		<h3 class="text-2xl font-bold text-secondary-100 m-4">Info About Us</h3>
		<p class="max-w-prose m-4">Lorem ipsum dolor sit amet consectetur adipisicing elit. Iusto repudiandae, earum ullam dolores cum dolorem. Culpa eveniet dolor provident eos. Alias aperiam laudantium molestiae aliquid. Quam officiis nostrum sapiente odio iure provident voluptate, ullam labore cumque reiciendis excepturi dolorum exercitationem!</p>
	</section>
	<!-- <CardWithIcon imgAlt={cardOne.imgAlt} imgSrc={cardOne.imgSrc} heading={cardOne.heading}></CardWithIcon>  -->
</main>

	
