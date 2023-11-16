<!-- YOU CAN DELETE EVERYTHING IN THIS PAGE -->
<script>
	import { LightSwitch } from '@skeletonlabs/skeleton';
	import Footer from "../lib/Footer.svelte";
	import { AppShell } from "@skeletonlabs/skeleton";
	import { AppBar } from '@skeletonlabs/skeleton';
	let title = 'hello';


</script>
<AppBar>{title}</AppBar>
<main >
<div class="grid grid-cols-3 grid-rows-2">
<img src='./assets/02-placeholder.jpg' alt="leaf" class="col-span-full col-start-1 row-start-1 row-span-full w-screen h-[600px]">
<div class=" max-h-[60%] z-10 bg-secondary-100 col-start-2 row-start-2  row-span-full text-surface-700 self-end p-4">
<h3 class="text-2xl pb-2">My Big Heading</h3>
<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Consequuntur cum cupiditate aperiam et natus ullam quo inventore, mollitia a sapiente.</p>
</div>
</div>

<div class="p-4 m-4 ">
	<h5>The Orange by Wendy Cope </h5>
<p>At lunchtime I bought a huge orange—<br />
The size of it made us all laugh.<br />
I peeled it and shared it with Robert and Dave—<br />
They got quarters and I had a half.<br />
</p>
<p>
And that orange, it made me so happy,<br />
As ordinary things often do<br />
Just lately. The shopping. A walk in the park.<br />
This is peace and contentment. It’s new.<br />
</p>
<p>
The rest of the day was quite easy.<br />
I did all the jobs on my list<br />
And enjoyed them and had some time over.<br />
I love you. I’m glad I exist.<br />
</p>
</div>
<p></p>
</main>

	
