<script lang="ts">
	import logo from '$lib/assets/logo_blue.svg';
	export let paragraphs: string[] = [];
	export let contact: string = '';
	export let contactName: string = '';
</script>

<div class="w-full">
	<div class="mx-auto my-4 max-w-lg text-center">
		<img class="mx-auto h-auto w-100" src={logo} alt="SZR Lav Elektronik Logo" />
		<h1 class="mt-6 text-5xl font-bold">Lav Elektronik</h1>
		<hr class="mt-6" />
		{#each paragraphs as pText}
			<p class="text-lg mt-2">{pText}</p>
		{/each}
		<hr class="mt-6" />
		<h2 class="mt-6 text-3xl">{contact}</h2>
		<p class="text-base mt-2">{contactName}</p>
		<p class="text-base mt-2">
			<a
				aria-label="Contact phone number"
				href="tel:+38163505192"
				class="hover:underline hover:text-slate-600 dark:hover:text-slate-300">063-505-192</a
			>
		</p>
	</div>
</div>