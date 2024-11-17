<script>
	import '../global.css';
	import Header from '$lib/components/Header.svelte';
</script>

<div class="container">
	<Header />

	<main>
		<slot />
	</main>
</div>

<style>
	@import url('https://fonts.googleapis.com/css2?family=Jersey+10&family=Roboto:wght@100;400;700&display=swap');
	.container {
		font-family: 'Roboto', sans-serif;
	}
</style>
