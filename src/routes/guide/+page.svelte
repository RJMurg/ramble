<script lang="ts">
	const underConstruction = 'Under Construction';
	const splitUC = underConstruction.split('');
</script>

<h1 class="text-8xl font-black">
	{#each splitUC as letter, i (i)}
		<span class={i % 2 === 0 ? 'text-neutral-500' : 'text-yellow-500'}>{letter}</span>
	{/each}
</h1>

<h2 class="text-2xl font-thin">This page isn't finished yet.</h2>
