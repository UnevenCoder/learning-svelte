<script>
	import Menu from "./Menu.svelte";
</script>

<main>
	<h1>hmm</h1>
	<Menu />
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #ff2a00;
		text-transform: uppercase;
		font-size: 2em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
		h1 {
			font-size: xx-large;
		}
	}
</style>
