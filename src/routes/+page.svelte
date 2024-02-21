<script>
	import Counter from './Counter.svelte';
	import welcome from '$lib/images/svelte-welcome.webp';
	import welcome_fallback from '$lib/images/svelte-welcome.png';
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<section>
	<h1>First Svelte Proyect</h1>
	<p>
		its faster than React and Next.js Lorem ipsum dolor, sit amet consectetur adipisicing elit. Eum
		vitae dignissimos saepe hic laboriosam voluptates adipisci! Nostrum explicabo hic recusandae est
		consectetur eius labore nihil numquam optio. Ipsa, vero laudantium?
	</p>
	<div class="img-main">
		<img
			class="img-main"
			src="https://res.cloudinary.com/dh01ngdjo/image/upload/v1708120673/FASHION/douma-demon-slayer_xlslp4.gif"
			alt=""
		/>
	</div>
</section>

<style>
	h1 {
		color: white;
	}
	p {
		color: white;
	}
	.img-main {
		display: flex;
		align-items: center;
		justify-content: center;
	}
</style>
