<script lang="ts">
	import blahaj from '$lib/assets/images/blahaj100.avif';
</script>

<div class="absolute left-0 top-0 -z-50 flex h-screen w-screen items-center overflow-hidden">
	<div
		class="h-full w-[200%] origin-left scale-150 transform bg-cover bg-center"
		style="background-image: url({blahaj});"
	></div>
</div>
<div class="absolute inset-0 flex items-center justify-center">
	<main class="z-10 w-fit space-y-4 rounded-md bg-black bg-opacity-60 p-8 text-white">
		<h1 class="text-4xl font-bold">bigblahaj.com</h1>
		<p>
			they're, in fact, big.
			<br />
			<em>-you, probably</em>
		</p>
	</main>
</div>
