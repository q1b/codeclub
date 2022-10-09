<script lang="ts">
	import { createCount } from './counter';
	const count = createCount();
</script>

<button on:click={count.increment}> + </button>
<h1>
	{$count}
</h1>
<button on:click={count.decrement}> - </button>
