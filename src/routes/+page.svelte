<script lang="ts">
	import Subheader from '../components/Subheader.svelte';
	import headshot from '$lib/assets/PXL_20230319_141209908.MP.jpg';
</script>

<main>
	<Subheader>Full-Stack Web Developer</Subheader>
	<div class="splash-caption">
		<img id="headshot-image" src={headshot} alt="Jonathan Dorety smiles" />
		<div class="caption">
			<p>
				I specialize in UI, data, and dev-ops. Open-source software is a particular passion of mine.
			</p>
		</div>
	</div>
</main>

<style>
	.splash-caption {
		position: relative;
	}
	#headshot-image {
		max-width: 350px;
	}
	.caption {
		position: relative;
		background-color: aqua;
		padding: 4px 14px;
		text-align: justify;
		width: 65%;
		font-size: 0.8rem;
		border-style: dashed;
		border-color: magenta;
		box-shadow: 6px 6px aqua, -6px -6px aqua, 6px -6px aqua, -6px 6px aqua;
	}
	.caption p {
		color: indigo;
		font-family: 'Courier New', Courier, monospace;
	}

	@media screen and (min-width: 400px) {
		#headshot-image {
			max-width: 300px;
		}
		.caption {
			width: 85%;
			bottom: 20px;
			left: 5%;
		}
		.caption p {
			font-size: 1.25rem;
		}
	}
</style>
