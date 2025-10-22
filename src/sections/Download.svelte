<script lang="ts">
	import { _ } from 'svelte-i18n';
</script>

<div
	class="flex min-h-screen min-w-screen flex-col justify-center bg-[url('/bg3.svg')] bg-cover bg-center bg-no-repeat"
>
	<h2 class="text-center text-6xl font-bold">{$_('download.download_arcnx')}</h2>
	<div class="mt-32 flex w-full flex-row flex-wrap justify-center gap-8">
		<div
			class="flex w-72 flex-col items-center rounded-3xl border-2 border-[#ffffff20] bg-[#11192899] p-8 px-12 text-center backdrop-blur-lg backdrop-saturate-180 transition-all duration-300 hover:border-[#ffffff47]"
		>
			<img src="/windows.svg" alt="Windows Logo" class="h-24 pb-4" />
			<p class="text-gray-300">v1.2.1</p>
			<p class="text-gray-300">250 MB</p>
			<p class="text-gray-300">Windows 10/11 (64 Bit)</p>
			<button
				class="mt-4 rounded-xl bg-white/10 px-4 py-2 text-white shadow-md transition-all duration-300 hover:cursor-pointer hover:bg-white/20"
				>Download</button
			>
		</div>
		<div
			class="flex w-72 flex-col items-center rounded-3xl border-2 border-[#ffffff20] bg-[#11192899] p-8 px-12 text-center backdrop-blur-lg backdrop-saturate-180 transition-all duration-300 hover:border-[#ffffff47]"
		>
			<img src="/apple.svg" alt="Apple Logo" class="h-24 pb-4" />
			<p class="text-gray-300">v1.2.1</p>
			<p class="text-gray-300">250 MB</p>
			<p class="text-gray-300">MacOS Tahoe+</p>
			<button
				class="mt-4 rounded-xl bg-white/10 px-4 py-2 text-white shadow-md transition-all duration-300 hover:cursor-pointer hover:bg-white/20"
				>Download</button
			>
		</div>
		<div
			class="flex w-72 flex-col items-center rounded-3xl border-2 border-[#ffffff20] bg-[#11192899] p-8 px-12 text-center backdrop-blur-lg backdrop-saturate-180 transition-all duration-300 hover:border-[#ffffff47]"
		>
			<img src="/linux.svg" alt="Tux" class="h-24 pb-4" />
			<p class="text-gray-300">v1.2.1</p>
			<p class="text-gray-300">220 MB</p>
			<p class="text-gray-300">x64 Distro</p>
			<button
				class="mt-4 rounded-xl bg-white/10 px-4 py-2 text-white shadow-md transition-all duration-300 hover:cursor-pointer hover:bg-white/20"
				>Download</button
			>
		</div>
		<div
			class="flex w-72 flex-col items-center rounded-3xl border-2 border-[#ffffff20] bg-[#11192899] p-8 px-12 text-center backdrop-blur-lg backdrop-saturate-180 transition-all duration-300 hover:border-[#ffffff47]"
		>
			<img src="/android.svg" alt="Android Logo" class="h-24 pb-4" />
			<p class="text-gray-300">v1.2.1</p>
			<p class="text-gray-300">160 MB</p>
			<p class="text-gray-300">Android 12+</p>
			<button
				class="mt-4 rounded-xl bg-white/10 px-4 py-2 text-white shadow-md transition-all duration-300 hover:cursor-pointer hover:bg-white/20"
				>Download</button
			>
		</div>
	</div>
</div>
