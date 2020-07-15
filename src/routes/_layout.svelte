<script>
import Header from '../components/Header.svelte';
export let segment; 
// segment nos permite identificar en que ruta estamos
</script>

<Header {segment} />
<main>
  <slot />
</main>
