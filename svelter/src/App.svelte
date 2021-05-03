<script>
	export let name;
</script>

<main>
	<div> 
	    <img width="250" height="250" src="/assets/images/si-logo-web-use-01.png" alt="Stunicon Logo">
		<h1>STUNICONS</h1>
		<p>Growing icon pack with 50+ editable icons in 3 styles for outstanding UI. <a href="https://svelte.dev/tutorial">Contribute on Github</a></p>
	</div>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>