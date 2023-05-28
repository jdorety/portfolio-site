<script>
	import Navbar from '../components/Navbar.svelte';
	const copyright = new Date().getFullYear();
</script>

<Navbar />
<div class="page-container">
	<h1>Jonathan Dorety</h1>
	<slot />
	<footer>
		<p>Copyright {copyright} Jonathan Dorety</p>
	</footer>
</div>

<style>
	h1 {
		font-family: Arial, Helvetica, sans-serif;
		font-size: 2.75rem;
		text-align: center;
	}
	div.page-container {
		max-width: 1200px;
		margin: 0 auto;
		margin-top: 60px;
	}
</style>
