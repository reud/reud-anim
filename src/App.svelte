<script lang="ts">
	import Header from "./components/Header.svelte";

	export let name: string;
</script>

<main>
	<Header />
	<div class="container-fluid" >
		<h1 class="title">
			reud the animation
		</h1>
		<span style="color: #768B98; font-size: 20px">シーズン1</span>
		<p>Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.</p>
	</div>
</main>

<style>
	body {
	}
	main {
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
		background: #0F171E;
		width: 100vw;
		height: 100vh;
	}

	.title {
		margin-top: 60px;
	}
	h1 {
		color: white;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>