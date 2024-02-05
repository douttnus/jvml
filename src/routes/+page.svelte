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
			<div class="flex flex-row-reverse items-center gap-4">
				<a href="https://github.com/douttnus" target="_blank">
					<img class="w-6 cursor-pointer" src="https://cdn-icons-png.flaticon.com/512/25/25231.png" alt="GitHub icon">
				</a>
			</div>
		</header>
		<div class="w-full mt-4">
			<p class="font-normal text-slate-850 text-sm">Desarrollador de Software con 2 años de experiência en el desarrollo de aplicaciones web.</p>
			<p class="font-normal text-slate-850 text-sm">Empezou en la carrera al final de 2022 y está mejorando cada día para entregar buenas soluciones.</p>
		</div>
	</div>
	<Actividades />
</main>

<style>
	main { max-width: 873px; }
	h1 { font-family: 'Zilla Slab'; }
	span, p { font-family: 'Fredoka'; }
</style>