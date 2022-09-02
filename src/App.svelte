<script>
	import WordleList from "./lib/WordleList.svelte";
</script>

<head
	><!-- Primary Meta Tags -->
	<title>World of Wordle</title>
	<meta name="title" content="World of Wordle" />
	<meta name="description" content="All the wordle games you can play today!" />
	<meta name="”robots”" content="index, follow" />
	<meta name="viewport" content="width=device-width, initial-scale=1.0" />
	<meta charset="UTF-8" />

	<!-- Open Graph / Facebook -->
	<meta property="og:type" content="website" />
	<meta property="og:title" content="World of Wordle" />
	<meta
		property="og:description"
		content="All the wordle games you can play today!"
	/>

	<!-- Twitter -->
	<meta property="twitter:title" content="World of Wordle" />
	<meta
		property="twitter:description"
		content="All the wordle games you can play today!"
	/>
</head>

<main>
	<h1>World of Wordle</h1>

	<WordleList />
</main>
