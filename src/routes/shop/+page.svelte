<script>
	import Shopcard from '../../components/Shopcard.svelte';
	export let data;

	const { products } = data;

	console.log(products);
</script>

<h2 class="text-3xl font-bold mb-10">Shop Page</h2>

<div class="flex gap-5 flex-wrap flex-col  md:flex-row">
	{#each products as product}
		<!-- <h2>{product.title}</h2> -->

		<Shopcard productData={product} />
	{/each}
</div>
