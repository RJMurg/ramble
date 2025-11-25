<script lang="ts">
	const underConstruction = 'Under Construction';
	const splitUC = underConstruction.split('');
</script>

<svelte:head>
	<!-- Primary Meta Tags -->
	<title>Ramble - The Guide</title>
	<meta name="title" content="The Lost Guide" />
	<meta name="description" content="An unfinished guide on how to run a soc" />

	<!-- Open Graph / Facebook -->
	<meta property="og:type" content="website" />
	<meta property="og:url" content="https://socs.rjm.ie/" />
	<meta property="og:title" content="The Lost Guide" />
	<meta property="og:description" content="An unfinished guide on how to run a soc" />
	<meta property="og:image" content="https://socs.rjm.ie/white-300ppi.png" />

	<!-- X (Twitter) -->
	<meta property="twitter:card" content="summary_large_image" />
	<meta property="twitter:url" content="https://metatags.io/" />
	<meta property="twitter:title" content="The Lost Guide" />
	<meta property="twitter:description" content="An unfinished guide on how to run a soc" />
	<meta property="twitter:image" content="https://socs.rjm.ie/white-300ppi.png" />

	<!-- Meta Tags Generated with https://metatags.io -->
</svelte:head>

<h1 class="text-8xl font-black">
	{#each splitUC as letter, i (i)}
		<span class={i % 2 === 0 ? 'text-neutral-500' : 'text-yellow-500'}>{letter}</span>
	{/each}
</h1>

<h2 class="text-2xl font-thin">This page isn't finished yet.</h2>
