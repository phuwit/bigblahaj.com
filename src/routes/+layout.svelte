<script lang="ts">
	import '../app.css';
	let { children } = $props();
</script>


<main class="min-h-screen h-fit w-screen">
	{@render children()}
</main>
