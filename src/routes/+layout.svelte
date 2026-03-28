<script lang="ts">
	import "../app.css";
	import favicon from '$lib/assets/favicon.svg';

	let { children } = $props();
</script>

<link
  rel="stylesheet"
  href="https://unpkg.com/98.css"
>
<img src="wallpaper.webp" alt="background" class="fixed inset-0 w-full h-full object-cover object-center -z-10">
<svelte:head>
	<link rel="icon" href={favicon} />
</svelte:head>

{@render children()}
