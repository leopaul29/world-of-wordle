<script>
	export let label;
	export let link;
	export let clicked;

	function handleClick() {
		clicked = true;
	}
</script>

<a href={link} target="_blank" rel="noopener noreferrer" on:click={handleClick}>
	<button class:clicked>{label}</button>
</a>

<style>
	.clicked {
		background-color: #646cff;
	}
</style>
