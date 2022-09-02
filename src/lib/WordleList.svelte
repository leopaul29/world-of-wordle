<script>
	import data from "../data/wordlelist.json";

	console.log(data);
</script>

<div class="wordleList">
	{#each data as wordle}
		<a href={wordle.link} target="_blank" rel="noopener noreferrer">
			<button>{wordle.label}</button>
		</a>
	{/each}
</div>

<style>
	.wordleList {
		max-width: 960px;
		padding: 40px;
	}
</style>
