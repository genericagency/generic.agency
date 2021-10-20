<script>
	import '../app.css';
</script>

<nav class="flex items-center justify-between w-screen h-6">
	<img src="" alt="" class="w-6 h-6">
	<div class="flex items-center justify-center">
		<a sveltekit:prefetch href="/">
			home
		</a>
		<a sveltekit:prefetch href="/about">
			about
	</a>
		<a sveltekit:prefetch href="/services">
			services
	</a>
		<a sveltekit:prefetch href="">

	</a>
	</div>
</nav>
<slot />
