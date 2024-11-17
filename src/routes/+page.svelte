<script>
	import Logo from '$lib/assets/logo_px.png';
</script>

<div class="main-container">
	<div class="penguin">
		<img src={Logo} alt="logo" />
	</div>
</div>

<style>
	.main-container {
		padding: 2rem;
		display: flex;
		justify-content: center;
		align-items: center;
		flex-direction: column;

		height: 80vh;
	}
	.penguin {
		animation: movePenguin 4s steps(5) infinite;
	}
	img {
		height: 120px;
	}
	@keyframes movePenguin {
		0% {
			transform: translateX(-100px) rotateY(180deg);
		}
		50% {
			transform: translateX(100px) rotateY(180deg);
		}
		51% {
			transform: translateX(100px) rotateY(0deg);
		}
		99% {
			transform: translateX(-100px) rotateY(0deg);
		}
		100% {
			transform: translateX(-100px) rotateY(180deg);
		}
	}
</style>
