<script>
	let name = 'world'
	import Login from './components/Login.svelte'
</script>

<svelte:head>
	<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/bulma/0.8.0/css/bulma.min.css" />
</svelte:head>

<main>
	<div>
		<h1>Hello {name}</h1>
		<Login />
	</div>
</main>

<style>
	main {
		padding: 20vh;
		display:grid;
		place-items: center;
	}
	h1 {
		color: #ff3e00;
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