<script>
	import '@skeletonlabs/skeleton/themes/theme-crimson.css';
	import '@skeletonlabs/skeleton/styles/skeleton.css';
	import '../app.postcss';

	import { AppBar, AppShell, Modal, Toast } from '@skeletonlabs/skeleton';
</script>

<svelte:head>
	<title>Untis ICS Sync</title>
</svelte:head>

<AppShell>
	<svelte:fragment slot="header">
		<AppBar>
			<svelte:fragment slot="lead">
				<h1 class="font-extrabold text-xl">&#9200; Untis ICS Sync</h1>
			</svelte:fragment>
		</AppBar>
	</svelte:fragment>
	<div class="p-4">
		<slot />
	</div>
</AppShell>
<Modal />
<Toast />
