<script>
	let count = 10;

	function Trying() {
		count += 1;
	}
</script>

<svelte:head>
	<title>About</title>
	<meta name="description" content="About this app" />
</svelte:head>

<div class="">
	<img
		width="500"
		src="https://res.cloudinary.com/dh01ngdjo/image/upload/v1703555845/PIXEL%20MOVIE/animations/show_fdtaoy.jpg"
		alt=""
	/>
	<div>
		<button on:click={Trying}>Search </button>

		<p>{count}</p>
	</div>
</div>
