<script lang="ts">
	import PageTransition from '../components/PageTransition.svelte';
	import Image from 'svelte-image';
</script>

<style lang="scss">

</style>

<svelte:head>
	<title>Sapper Template</title>
</svelte:head>

<PageTransition>

	<h1>Home</h1>
	<div class="row">
		<div class="col-6">
			<Image src="img/Virginia_Beach-2019_09_01-3226.jpg" />
			<Image src="img/Virginia_Beach-2019_09_01-3249.jpg" />
		</div>
		<div class="col-6">
			<Image src="img/Virginia_Beach-2019_09_01-3232.jpg" />
			<Image src="img/Virginia_Beach-2019_09_01-3250.jpg" />
		</div>
	</div>
	<Image src="img/Virginia_Beach-2019_09_01-3253.jpg" />
	<Image src="img/Virginia_Beach-2019_09_01-3254.jpg" />
	<Image src="img/Virginia_Beach-2019_09_01-3261.jpg" />
	<Image src="img/Virginia_Beach-2019_09_01-3316.jpg" />
	<Image src="img/Virginia_Beach-2019_09_01-3354.jpg" />

</PageTransition>