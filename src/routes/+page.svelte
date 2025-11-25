<script lang="ts">
	import { Button } from '$lib/components/shad/ui/button/index';
	import { ScrollTextIcon } from '@lucide/svelte';
</script>

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
