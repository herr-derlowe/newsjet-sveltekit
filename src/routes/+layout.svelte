<script lang="ts">
	import 'css/app.css';
	import core from 'franken-ui/js/core.iife?url';
	import icon from 'franken-ui/js/icon.iife?url';

	let { children } = $props();
</script>

<svelte:head>
	<script type="module" src={core}></script>
	<script type="module" src={icon}></script>
</svelte:head>

{@render children()}
