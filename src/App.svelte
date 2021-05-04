<script>
	export let name;
</script>

<main>
	<section class="banner-inicial">
		<!--<h1>cardapio de {name}!</h1> -->
	</section>
	<h1>Hello {name}!</h1>
	<p>
		This is a starter template for a Svelte PWA, based in the <a
			href="https://github.com/sveltejs/template"
			target="_blank">Svelte template</a
		>
	</p>
	<p>
		You will find the manifest.json file and the service-worker.js file in
		the public folder
	</p>
	<p>
		To update the proper icons for the PWA check <i>/public/images/icons</i>
	</p>
</main>

<style>
	.banner-inicial {
		width: 100%;
		height: 200px;
		background: red;
		padding: 1px;
		background-image: url(/images/banners/banner1.webp);
		background-size: 100%;
		background-position: 0% 99%;
	}
</style>
