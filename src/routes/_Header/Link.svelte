<script>
	export let path, active;
</script>

<li>
	<a href={path} class:active class="text-basics-900 uppercase font-thin tracking-wider border-b-4 border-transparent hover:border-b-primary focus:border-b-primary">
		<slot />
	</a>
</li>

<style>
  a {
	font-size: var(--font-100);
  }
	.active {
		border-bottom: 4px solid var(--color);
	}
</style>
