<svelte:head>
  <link href="https://fonts.googleapis.com/css?family=Fira+Code" rel="stylesheet">
</svelte:head>

<script lang="ts">
	import '../app.css';
	let { children } = $props();
</script>

{@render children()}
