<script>
	import Actividades from '../lib/actividades/Actividades.svelte';
</script>

<div class="w-full">
	<img class="w-full h-48 object-cover" src="https://images.fineartamerica.com/images/artworkimages/mediumlarge/3/flying-carpet-viktor-vasnetsov-1880-classical-aesthetics.jpg" alt="">
</div>
<main class="mx-auto mt-12">
	<div>
		<header class="flex items-center justify-between">
			<div class="flex flex-col w-full">
				<h1 class="text-3xl font-bold">JOÃO MARCON</h1>
				<span class="text-sm text-slate-700">São Paulo, Brasil</span>
			</div>
			<div class="flex flex-row-reverse items-center gap-6">
				<a class="flex items-center gap-2" href="https://masto.es/@douttnus" target="_blank">
					<img class="w-6 cursor-pointer" src="https://cdn.iconscout.com/icon/free/png-256/free-mastodon-3521565-2944983.png" alt="Mastodon icon">
					<label for="mastodon" class="text-sm cursor-pointer transition ease-in-out duration-300 hover:text-slate-900">Social</label>
				</a>
				<a class="flex items-center gap-2" href="https://github.com/douttnus" target="_blank">
					<img class="w-6 cursor-pointer" src="https://cdn-icons-png.flaticon.com/512/25/25231.png" alt="GitHub icon">
					<label for="fuente" class="text-sm cursor-pointer transition ease-in-out duration-300 hover:text-slate-900">Fuente</label>
				</a>
			</div>
		</header>
		<div class="w-full mt-4">
			<p class="font-normal text-slate-850 text-sm">Desarrollador de Software con 2 años de experiência en el desarrollo de aplicaciones web.</p>
			<p class="font-normal text-slate-850 text-sm">Empezou en la carrera al final de 2022 y está mejorando cada día para entregar buenas soluciones.</p>
		</div>
	</div>
	<Actividades />
	<div class="mt-4">
		<h2 class="text-2xl mb-1 font-medium" style="font-weight: 600;">CONTACTO</h2>
		<span class="text-sm">
			Si está interesado en hablar conmigo, póngase en contacto a través de la red social
			<a href="https://masto.es/@douttnus" target="_blank" class="font-medium cursor-pointer transition ease-in-out duration-300 hover:text-cyan-700">Mastodon</a>
		</span>
	</div>
	<div class="border mt-6"></div>
</main>
<footer class="text-center mt-4">
	<p>© 2024 João Marcon. Todos los derechos reservados.</p>
</footer>

<style>
	main { max-width: 873px; }
	h1, h2 { font-family: 'Zilla Slab'; }
	span, p { font-family: 'Fredoka'; }
</style>