<script lang="ts">
	import '../app.css';
	let { children } = $props();
</script>


<div class="min-h-screen h-fit w-screen">
	{@render children()}
</div>
