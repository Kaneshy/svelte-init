<script>
	import Popup from '../Popup.svelte';
	let mensaje = '¡Hola desde el componente principal!';
</script>

<svelte:head>
	<title>About</title>
	<meta name="description" content="About this app" />
</svelte:head>

<div class="text-column">
	<h1>About this app</h1>

	<p>
		Fisrt Svelte Proyect Lorem ipsum dolor sit amet consectetur, adipisicing elit. Eos aliquid
		praesentium ab cupiditate id ea dolore non vel harum incidunt ipsa enim, quod laudantium
		necessitatibus accusantium quos, error esse consectetur! Lorem ipsum dolor sit amet consectetur
		adipisicing elit. Debitis harum porro voluptatem animi, maxime possimus aliquam exercitationem
		commodi vitae dolorum! Eaque aperiam laborum ratione optio. Aspernatur, impedit. Similique, sed
		cumque.
	</p>
	<Popup />
</div>

<style>
	h1 {
		color: white;
	}
	p {
		color: rgb(209, 209, 209);
	}
</style>
