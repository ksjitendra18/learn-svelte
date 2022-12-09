<script>
	export let productData;
</script>

<div class="card border-solid border-2 border-black rounded-lg p-5">
	<div class="img">
		<img src={productData.images[0]} alt="" class="h-[200px]" />
	</div>
	<div class="text-content mt-5">
		{productData.title}
	</div>
</div>
