<script>
	import { name, greeting } from './stores.js';
</script>

<h1>{$greeting}</h1>
<input bind:value={$name} />
<p>Store value for name : {$name}</p>

<button on:click={() => $name += '!'}>
	Add exclamation mark!
</button>
