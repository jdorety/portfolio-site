<script lang="ts">
	import Navbar from '../components/Navbar.svelte';
	import Footer from '../components/Footer.svelte';

	const copyright = new Date().getFullYear();
</script>

<Navbar />
<div class="page-container">
	<h1>Jonathan Dorety</h1>
	<slot />
</div>
<Footer {copyright} />

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

		div.page-container {
			margin-top: 75px;
		}
	}
</style>
