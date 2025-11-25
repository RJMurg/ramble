<script lang="ts">
	import wishlist from '$lib/content/wishlist.json';
</script>

<svelte:head>
	<!-- Primary Meta Tags -->
	<title>Ramble - The Wishlist</title>
	<meta name="title" content="RJM's Wishlist of Soc Ideas" />
	<meta
		name="description"
		content="What stupid ideas is Ruán thinking of now? Reach out if you'd like to make one happen!"
	/>

	<!-- Open Graph / Facebook -->
	<meta property="og:type" content="website" />
	<meta property="og:url" content="https://socs.rjm.ie/" />
	<meta property="og:title" content="RJM's Wishlist of Soc Ideas" />
	<meta
		property="og:description"
		content="What stupid ideas is Ruán thinking of now? Reach out if you'd like to make one happen!"
	/>
	<meta property="og:image" content="https://socs.rjm.ie/white-300ppi.png" />

	<!-- X (Twitter) -->
	<meta property="twitter:card" content="summary_large_image" />
	<meta property="twitter:url" content="https://metatags.io/" />
	<meta property="twitter:title" content="RJM's Wishlist of Soc Ideas" />
	<meta
		property="twitter:description"
		content="What stupid ideas is Ruán thinking of now? Reach out if you'd like to make one happen!"
	/>
	<meta property="twitter:image" content="https://socs.rjm.ie/white-300ppi.png" />

	<!-- Meta Tags Generated with https://metatags.io -->
</svelte:head>

<div class="mb-4 w-full text-center">
	<h1 class="text-8xl font-black">The Wishlist</h1>
	<h2 class="text-light text-2xl italic">Things I wish I could've done</h2>
	<h2 class="text-light text-xl">Contact me if you want help!</h2>
</div>

<div class="flex h-screen w-screen flex-col overflow-scroll p-8">
	{#each wishlist as wish (wish.title)}
		<div class="mb-4 flex flex-col items-start">
			<h1 class="text-2xl font-bold">{wish.title}</h1>
			<p class="w-full text-pretty">{wish.body}</p>
		</div>
	{/each}
</div>
