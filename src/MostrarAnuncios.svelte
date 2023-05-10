<script>
	export let anuncios
</script>

{#each anuncios as anuncio}
<div>
	<p>
		{anuncio.contido}
	</p>
	<p>
		{anuncio.contacto}
	</p>
</div>
{/each}