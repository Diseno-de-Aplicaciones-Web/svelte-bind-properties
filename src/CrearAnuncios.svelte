<script>
export let anuncios
let contido
let contacto
function manexadorClick() {
	const novosAnuncios = [...anuncios]
	novosAnuncios.push({contido, contacto})
	anuncios = novosAnuncios
}
</script>

<input bind:value={contido} placeholder="Pon o contido...">
<input bind:value={contacto} placeholder="Pon o contacto...">
<button on:click={manexadorClick}>
	Publicar
</button>
