<script>
	import { AppBar, AppShell } from "@skeletonlabs/skeleton";

  let title = "About Me ;p"
</script>

<AppShell>
	<AppBar>
		<svelte:fragment slot="headline"> <h2 class="text-5xl text-center">{title}</h2></svelte:fragment>
		</AppBar>

	<!-- Router Slot -->
	<slot />
	
	<svelte:fragment slot="pageFooter">Page Footer</svelte:fragment> 
	<!-- (footer) -->
</AppShell>
