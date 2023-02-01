<script lang="ts">
	import '@picocss/pico'
	import Header from './Header.svelte';
</script>

<div class="app">
	<Header/>
	<slot />
</div>

<style>
	.app {
		margin: 0px 100px;
	}
</style>