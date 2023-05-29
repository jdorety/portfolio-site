<script lang="ts">
	import Subheader from '../components/Subheader.svelte';
	import headshot from '$lib/assets/PXL_20230319_141209908.MP.jpg';
</script>

<Subheader>Full-Stack Web Developer</Subheader>
<div class="splash-caption">
	<img id="headshot-image" src={headshot} alt="Jonathan Dorety smiles" />
	<div class="caption">
		<p>
			I specialize in UI, data, and devops. Open-source software is a particular passion of mine.
		</p>
	</div>
</div>

<style>
	.splash-caption {
		position: relative;
    top: 20px;
	}
	#headshot-image {
		max-width: 150px;
	}
	.caption {
		position: absolute;
		top: -20px;
		width: 65%;
		right: 0;
		background-color: aqua;
		padding: 4px 14px;
		text-align: justify;
	}
	.caption p {
		color: indigo;
		font-family: 'Courier New', Courier, monospace;
	}

	@media screen and (min-width: 400px) {
		#headshot-image {
			max-width: 300px;
		}
	}
</style>
