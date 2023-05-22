<script>
	import './styles.css';
	import Header from './Header.svelte';
	import Footer from './Footer.svelte';
</script>

<div class="app">
	<Header />

	<div class="content">
		<slot />
	</div>

	<Footer />
</div>

<style>
	.content {
		padding-bottom: 2.5em;
	}
	.app {
		padding: 20px;
		max-width: 720px;
		margin: auto;
		position: relative;
		display: flex;
		flex-direction: column;
		align-items: center;
		min-height: 100vh;
	}
</style>
