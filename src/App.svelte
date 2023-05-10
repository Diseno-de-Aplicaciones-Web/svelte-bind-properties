<script>
	import MostrarAnuncios from "./MostrarAnuncios.svelte"
	import CrearAnuncios from "./CrearAnuncios.svelte"
	let anuncios = [
		{
			contido: "Teño mel",
			contacto: "otipodomel@cousas.gal"
		}
	];
</script>

<h1>
	Anuncios
</h1>

<MostrarAnuncios anuncios={anuncios}/>
<CrearAnuncios bind:anuncios={anuncios}/>