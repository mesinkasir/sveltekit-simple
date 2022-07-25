<script>
	import Widget from '$lib/widget/Navbar.svelte';
	import '../app.css';
</script>

<div class="container">
<Widget />
<div class="row mt-5">
<main class="col-md-8 offset-md-2 mt-5">
	<slot />
	<div class="text-center mt-5 border border-dark p-3 rounded">
	<h3>Contact Us</h3>
	<p>Hubungi kami untuk kebutuhan mesin kasir anda.</p>

	</div>
</main>

</div>

<footer class="mt-5 text-center">
	<p>visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to learn SvelteKit</p>
</footer>
</div>
