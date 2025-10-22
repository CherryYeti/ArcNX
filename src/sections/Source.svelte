<script lang="ts">
	import { _ } from 'svelte-i18n';
	import { Icon, ArrowUpRight } from 'svelte-hero-icons';
</script>

<div
	class="flex min-h-screen min-w-screen flex-col items-center justify-center bg-[url('/bg2.svg')] bg-cover bg-center bg-no-repeat"
>
	<h2 class="text-center text-6xl font-bold">{$_('source.open_source')}</h2>
	<h4 class="pt-8 text-xl">{$_('source.contribute_to_arcnx')}</h4>
	<div class="flex flex-row gap-8">
		<div
			class="mt-16 flex w-72 flex-col items-center rounded-3xl border-2 border-[#ffffff20] bg-[#11192899] p-8 px-12 text-center backdrop-blur-lg backdrop-saturate-180 transition-all duration-300 hover:cursor-pointer hover:border-[#ffffff47]"
		>
			<img src="/github.svg" alt="Github Logo" class="h-24 pb-4" />
			<div class="flex flex-row items-center text-center">
				<p>
					{$_('source.contribute')}
				</p>
				<Icon src={ArrowUpRight} size="16" class="ml-2"></Icon>
			</div>
		</div>
		<div
			class="mt-16 flex w-72 flex-col items-center rounded-3xl border-2 border-[#ffffff20] bg-[#11192899] p-8 px-12 text-center backdrop-blur-lg backdrop-saturate-180 transition-all duration-300 hover:cursor-pointer hover:border-[#ffffff47]"
		>
			<img src="/discord.svg" alt="Discord Logo" class="h-24 pb-4" />
			<div class="flex flex-row items-center text-center">
				<p>
					{$_('source.join_discord')}
				</p>
				<Icon src={ArrowUpRight} size="16" class="ml-2"></Icon>
			</div>
		</div>
	</div>
</div>
