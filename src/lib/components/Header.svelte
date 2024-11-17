<script lang="ts">
	import Logo from '$lib/assets/logo_px.png';
</script>

<header>
	<div class="logo">
		<img src={Logo} alt="logo" />
		<h1>PPPenguin</h1>
	</div>
	<p>coming soon ...</p>
</header>

<style>
	:global(body) {
		--color-bg: rgb(240, 240, 240);
		--color-text: rgb(0, 0, 0);
		--color-border: rgb(200, 200, 200);
	}
	header {
		display: flex;
		justify-content: space-between;
		align-items: center;
		padding: 0.5rem 1rem;
		font-family: 'Jersey 10', sans-serif;
	}

	.logo {
		display: flex;
		align-items: center;
		gap: 0.5rem;
	}

	.logo h1 {
		margin: 0;
		font-size: 1.5rem;
		font-weight: 500;
		color: var(--color-text);
	}

	.logo img {
		height: 1.5rem;
		transform: rotateY(180deg);
	}
</style>
