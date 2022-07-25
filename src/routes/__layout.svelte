<script>
	import Widget from '$lib/widget/Navbar.svelte';
	import Contact from '$lib/widget/Contact.svelte';
	import data from '../data/widget.json';
	import '../app.css';
</script>

<div class="container">
<Widget />
<div class="row mt-5">
<main class="col-md-8 offset-md-2 mt-5">
	<slot />
<Contact/>
</main>

</div>

<footer class="mt-5 text-center">
	<p>built with <a href="https://kit.svelte.dev">Sveltekit</a> Repo On <a href="https://github.com/mesinkasir/sveltekit-simple">Github</a> Host by <a href="https://cloudflare.com">Cloudflare</a></p>
</footer>
</div>
