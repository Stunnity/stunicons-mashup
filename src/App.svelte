<script>
	const icons = [
		{name: 'Home', icon: 'si-home'},
		{name: 'Menu Bar', icon: 'si-menu-bar'},
		{name: 'Plus', icon: 'si-plus'},
		{name: 'Search', icon: 'si-search'},
		{name: 'User', icon: 'si-user'},
		{name: 'Arrow Down', icon: 'si-arrow-down'},
		{name: 'Arrow Left', icon: 'si-arrow-left'},
		{name: 'Gmail', icon: 'si-gmail'},
		{name: 'Heart', icon: 'si-heart'},
		{name: 'Github', icon: 'si-github'},
		{name: 'Slack', icon: 'si-slack'},
	]
</script>

<section>
	<main>
		<div class="lander">  
			<img width="200" height="200" src="/assets/images/si-logo-web-use-01.png" alt="Stunicon Logo">
			<span>Stunicons</span>
		</div>
	</main>
	<div class="example">
		<h3>Examples</h3>
		<div class="grid-container">
			{#each icons as icon, i}
				<div class="grid-item">
					<div class="icon">
						<i class="{icon.icon}"></i>
					</div>
				</div>
			{/each}
		</div>
	</div>
</section>

<footer>
   <p class="footer-txt">Made by <span>Stunnity</span></p>
</footer>
<style>
	
	section {
		height: 90vh;
	}
	
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	.lander {
		display: flex;
		align-items: center;
		justify-content: center;
		margin-bottom: 4rem;
	}

	.lander span {
		font-size: 4rem;
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