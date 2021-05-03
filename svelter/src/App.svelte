<script>
</script>

<main>
	<div class="lander">  
	    <img width="200" height="200" src="/assets/images/si-logo-web-use-01.png" alt="Stunicon Logo">
		<!-- <h1>STUNICONS</h1>
		<p>Growing icon pack with 50+ editable icons in 3 styles for outstanding UI. <a href="https://svelte.dev/tutorial">Contribute on Github</a></p> -->
	</div>
</main>
<div class="example">
	<h3>Examples</h3>
	
<div class="grid-container">
	<div class="grid-item">
		<i class="si-location-off"></i>
	</div>
	<div class="grid-item">2</div>
	<div class="grid-item">3</div>
	<div class="grid-item">4</div>
	<div class="grid-item">5</div>
	<div class="grid-item">6</div>
	<div class="grid-item">7</div>
	<div class="grid-item">8</div>
	<div class="grid-item">9</div>
</div>
</div>

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

	.grid-container {
		display: grid;
		grid-template-columns: auto auto auto auto auto auto;

		padding: 10px;
	}
	.grid-item {
		border: 1px solid rgba(0, 0, 0, 0.8);
		padding: 20px;
		font-size: 30px;
		margin: 1rem 2rem;
  		text-align: center;
	}
	.example {
		padding: 0 6rem;
	}
	.example h3 {
		color: #ff3e00;
		text-decoration: underline;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>