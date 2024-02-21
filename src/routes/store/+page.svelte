<svelte:head>
	<title>About</title>
	<meta name="description" content="About this app" />
</svelte:head>

<script>
    let arrayA = [1,2,3,4,5,6]
</script>

<div class="text-column">
	<h1>Store</h1>
	<div class="grid-a">
        {#each arrayA as target, i}
        <div class="b">
            <img width="250" src="https://res.cloudinary.com/dh01ngdjo/image/upload/v1704496776/FASHION/Bags___Accessories_Hats_Scarves___Gloves_Mega_Menu_Espots_M_jznuam.jpg" alt="">
        </div>
        {/each}
    </div>
</div>

<style>
    .b {
        padding: 3px;
        display: flex;
        align-items: center;
        justify-content: center;
    }
	h1 {
		color: white;
	}

	.grid-a {
        background-color: white;
		width: 100%;
		padding: 15px;
		display: grid;
		grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
		margin: 0 auto;
		gap: 20px;
		row-gap: 50px;
	}

	
</style>
