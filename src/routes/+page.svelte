<script lang="ts">
	import { Button } from '$lib/components/shad/ui/button/index';
	import { ScrollTextIcon } from '@lucide/svelte';
</script>

<svelte:head>
	<!-- Primary Meta Tags -->
	<title>Ramble - RJM's Thoughts on Socs</title>
	<meta name="title" content="Ramble - RJM's Thoughts on Socs" />
	<meta
		name="description"
		content="Go through RJM's wishlist of society ideas, and his guide on how to run socs. If you trust him, that is."
	/>

	<!-- Open Graph / Facebook -->
	<meta property="og:type" content="website" />
	<meta property="og:url" content="https://socs.rjm.ie/" />
	<meta property="og:title" content="Ramble - RJM's Thoughts on Socs" />
	<meta
		property="og:description"
		content="Go through RJM's wishlist of society ideas, and his guide on how to run socs. If you trust him, that is."
	/>
	<meta property="og:image" content="https://socs.rjm.ie/white-300ppi.png" />

	<!-- X (Twitter) -->
	<meta property="twitter:card" content="summary_large_image" />
	<meta property="twitter:url" content="https://metatags.io/" />
	<meta property="twitter:title" content="Ramble - RJM's Thoughts on Socs" />
	<meta
		property="twitter:description"
		content="Go through RJM's wishlist of society ideas, and his guide on how to run socs. If you trust him, that is."
	/>
	<meta property="twitter:image" content="https://socs.rjm.ie/white-300ppi.png" />

	<!-- Meta Tags Generated with https://metatags.io -->
</svelte:head>

<h1 class="text-8xl font-black">Ramble</h1>
<h2 class="text-2xl font-thin italic">Ruán's unsolicited opinions on Societies</h2>
<div class="mt-4 flex flex-row items-center justify-center">
	<Button class="mr-4" href="/wishlist">
		<ScrollTextIcon />
		Wishlist
	</Button>

	<Button variant="secondary" href="/guide">
		<ScrollTextIcon />
		RJM's Guide
	</Button>
</div>
