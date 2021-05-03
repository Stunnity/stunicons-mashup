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
		<div class="icon">
			<i class="si-location-off"></i>
		</div>
	</div>
	<div class="grid-item">
		<i class="si-location-off"></i>
	</div>
	<div class="grid-item">
		<i class="si-location-off"></i>
	</div>
	<div class="grid-item">
		<i class="si-location-off"></i>
	</div>
	<div class="grid-item">
		<i class="si-location-off"></i>
	</div>
	<div class="grid-item">
		<i class="si-location-off"></i>
	</div>
	<div class="grid-item">
		<i class="si-location-off"></i>
	</div>
	<div class="grid-item">
		<i class="si-location-off"></i>
	</div>
	<div class="grid-item">
		<i class="si-location-off"></i>
	</div>
	<div class="grid-item">
		<i class="si-location-off"></i>
	</div>
	<div class="grid-item">
		<i class="si-location-off"></i>
	</div>
	<div class="grid-item">
		<i class="si-location-off"></i>
	</div>
	<div class="grid-item">
		<i class="si-location-off"></i>
	</div>
	<div class="grid-item">
		<i class="si-location-off"></i>
	</div>
	<div class="grid-item">
		<i class="si-location-off"></i>
	</div>
	<div class="grid-item">
		<i class="si-location-off"></i>
	</div>
	<div class="grid-item">
		<i class="si-location-off"></i>
	</div>
	<div class="grid-item">
		<i class="si-location-off"></i>
	</div>
</div>

</div>

<footer>
   <p class="footer-txt">Made by <span>Stunnity</span></p>
</footer>
<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}


	.grid-container {
		display: grid;
		grid-template-columns: auto auto auto auto auto auto;
		padding: 10px;
	}
	.grid-item {
		border: none;
		background-color: #f8f8f8;
		border-radius: 6px;
		height: 5rem;
		display: flex;
    	align-items: center;
    	justify-content: center;
		width: 7rem;
		font-size: 20px;
		margin: 1rem 2rem;
  		text-align: center;
	}
	.icon {
		display: flex;
		flex-direction: column;
		align-items: center;
		height: fit-content;
		width: fit-content;
	}
	.example {
		padding: 0 6rem;
	}
	.example h3 {
		color: #ff3e00;
		text-decoration: underline;
	}

	footer {
		padding: 0 3rem ;
	}
	.footer-txt {
		text-align: right;
	}

	.footer-txt span {
		color:  #ff3e00;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>