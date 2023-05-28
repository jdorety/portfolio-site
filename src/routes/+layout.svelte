<script>
	const copyright = new Date().getFullYear();
</script>

<div class="page-container">
	<h1>Jonathan Dorety</h1>
	<slot />
	<footer>
		<p>Copyright {copyright} Jonathan Dorety</p>
	</footer>
</div>

<style>
	h1 {
		font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode',
			Geneva, Verdana, sans-serif;
		font-size: 2.75rem;
		text-align: center;
	}
	div.page-container {
		max-width: 1200px;
		margin: 0 auto;
	}
</style>
