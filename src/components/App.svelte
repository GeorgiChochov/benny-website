<script>
	import NavigationEn from "./navigation/NavigationEn.svelte"
	import NavigationBg from "./navigation/NavigationBg.svelte"

	let language = "bg"
</script>

{#if language === "en"}
	<NavigationEn/>
{:else}
	<NavigationBg/>
{/if}

