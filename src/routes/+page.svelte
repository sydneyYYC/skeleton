<!-- YOU CAN DELETE EVERYTHING IN THIS PAGE -->
<script>
	import { AppShell } from "@skeletonlabs/skeleton";
	import { AppBar } from '@skeletonlabs/skeleton';
	import Footer from "../lib/Footer.svelte";
	let title = "Hello!"
</script>


<AppShell>
	<AppBar>
		<svelte:fragment slot="headline"> <h2 class="text-5xl text-center">{title}</h2></svelte:fragment>
		</AppBar>

	<!-- Router Slot -->
	
	<slot />
	<svelte:fragment slot="pageFooter"><Footer/></svelte:fragment>
	<!-- (footer) -->
</AppShell>
