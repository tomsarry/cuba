<script>
	import { page } from '$app/stores';
	// import github from '$lib/images/github.svg';
</script>

<header>
	<nav>
		<span aria-current={$page.url.pathname === '/' ? 'page' : undefined} class="nav-link">
			<a href="/">Home</a>
		</span>
	</nav>
</header>

<style>
	nav {
		margin: 0.7em;
	}

	.nav-link[aria-current='page'] {
		opacity: 0;
	}
</style>
