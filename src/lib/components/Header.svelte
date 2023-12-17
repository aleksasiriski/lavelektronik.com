<script lang="ts">
	import logo from '$lib/assets/logo_blue.svg';
</script>

<!-- Header section -->
<header class="h-20 w-full text-slate-100 dark:text-slate-200 bg-slate-800 dark:bg-slate-900">
	<div class="mx-4">
		<div class="mx-auto flex items-center">
			<div>
				<a aria-label="SZR Lav Elektronik Logo" href="/">
					<img class="h-20 w-20" src={logo} alt="SZR Lav Elektronik Logo" />
				</a>
			</div>
			<div class="flex items-center h-20">
				<a aria-label="Srpski" href="/"><p class="text-lg hover:text-slate-500 mx-1">Srpski</p></a>
				<a aria-label="English" href="/en"><p class="text-lg hover:text-slate-500 mx-1">English</p></a>
				<a aria-label="Русский" href="/ru"><p class="text-lg hover:text-slate-500 mx-1">Русский</p></a>
			</div>
		</div>
	</div>
</header>
