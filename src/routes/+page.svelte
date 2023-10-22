<script>
	let i = 0;
</script>

<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>

<div class="text-xl">f</div>
<h1 class="text-4xl">
	{i}
</h1>

<button on:click={() => (i += 1)}>+</button>
<button on:click={() => (i -= 1)}>-</button>
