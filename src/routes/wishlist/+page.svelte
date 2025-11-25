<script lang="ts">
	import wishlist from '$lib/content/wishlist.json';
</script>

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
