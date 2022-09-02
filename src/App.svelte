<script>
	import svelteLogo from "./assets/svelte.svg";
	import WordleList from "./lib/WordleList.svelte";
</script>

<main>
	<a
		href="https://www.nytimes.com/games/wordle/index.html"
		target="_blank"
		rel="noopener noreferrer"
		class="titleLink"
	>
		<h1>World of Wordle</h1>
	</a>

	<WordleList />
</main>

<style>
	.titleLink {
		color: rgba(255, 255, 255, 0.87);
	}
</style>
