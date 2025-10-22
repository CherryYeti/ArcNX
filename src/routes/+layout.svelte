<script lang="ts">
	import { register, init, getLocaleFromNavigator } from 'svelte-i18n';

	register('en', () => import('../locales/en.json'));
	register('ja-JP', () => import('../locales/ja-JP.json'));

	init({
		fallbackLocale: 'ja-JP',
		initialLocale: getLocaleFromNavigator()
	});

	import '../app.css';
	import favicon from '$lib/assets/favicon.svg';
	import Navbar from '../components/Navbar.svelte';
	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
</svelte:head>

<div class="min-h-screen min-w-screen bg-[#001220] text-white">
	<Navbar />
	{@render children?.()}
</div>
