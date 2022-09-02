<script>
	import WordleButton from "./WordleButton.svelte";
	import data from "../data/wordlelist.json";
</script>

<div class="wordleList">
	{#each data as wordle}
		<WordleButton label={wordle.label} link={wordle.link} clicked={false} />
	{/each}
</div>

<style>
	.wordleList {
		max-width: 960px;
		padding: 40px;
	}
</style>
