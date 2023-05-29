<script>
	import Navbar from '../components/Navbar.svelte';
	import Footer from '../components/Footer.svelte';
</script>

<Navbar />
<div class="page-container">
	<h1>Jonathan Dorety</h1>
	<slot />
</div>
<Footer />

<style>
	h1 {
		font-family: Arial, Helvetica, sans-serif;
		font-size: 2.25rem;
		text-align: center;
	}
	
	div.page-container {
		max-width: 1200px;
		margin: 0 auto;
		margin-top: 60px;
	}
	
	@media screen and (min-width: 400px) {
		h1 { 
			font-size: 2.75rem;
		}
	}
</style>
