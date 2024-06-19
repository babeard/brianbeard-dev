<script lang="ts">
	import Footer from './footer.svelte';
	import Header from './header.svelte';

	import '../app.css';
</script>

<div class="layout">
	<Header />

	<main>
		<slot />
	</main>

	<Footer />
</div>
