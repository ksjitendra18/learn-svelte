<script>
	import '../app.css';
	import Header from '../Header.svelte';
</script>

<div>
	<header class="app w-[1180px] mx-auto px-5">
		<Header />
	</header>

	<main class="app w-[1180px] mx-auto px-5">
		<slot />
	</main>
</div>
