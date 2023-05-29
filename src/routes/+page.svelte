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
		/* display: absolute; */
		margin: 0 5%;
	}
	#headshot-image {
		max-width: 150px;
	}
	.caption {
		position: relative;
		bottom: 50px;
		left: 25%;
		max-width: 250px;
		background-color: aqua;
		padding: 4px 14px;
		text-align: justify;
	}
	.caption p {
		color: indigo;
	}

	@media screen and (min-width: 400px) {
		#headshot-image {
			max-width: 300px;
		}
	}
</style>
