<script>
	import Download from '../sections/Download.svelte';
	import Landing from '../sections/Landing.svelte';
	import { waitLocale } from 'svelte-i18n';
	import Source from '../sections/Source.svelte';
</script>

{#await waitLocale()}
	<p>Loading...</p>
{:then}
	<Landing />
	<Source />
	<Download />
{/await}
