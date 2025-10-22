<script lang="ts">
	import { _ } from 'svelte-i18n';
</script>

<!--  bg-[url('/bg.svg')] bg-cover bg-center bg-no-repeat -->
<div class="min-h-screen min-w-screen bg-[url('/bg.svg')] bg-cover bg-center bg-no-repeat">
	<div
		class="mx-auto flex h-screen w-full max-w-xl flex-col items-center justify-center text-center"
	>
		<h1 class="text-7xl font-bold">ArcNX</h1>
		<p class="mx-4 pt-4 text-xl">{$_('landing.description')}</p>
	</div>
</div>

<style>
	@import url('https://fonts.googleapis.com/css2?family=Pacifico&display=swap');
	h1 {
		font-family: 'Pacifico', cursive;
	}
</style>
