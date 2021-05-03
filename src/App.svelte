<script>
	import Nested from "./Nested.svelte";
	export let name;
	let yes = false;
	let title = "bui duc hieu";
</script>

<main>
	<h1>Hello {name}!</h1>
	<p>Hello ádsadsadsadsadsad {title}</p>
	<Nested />
	<label>
		<input type="checkbox" bind:checked={yes} />
		Yes! Nếu bạn muốn đi cùng tôi?
	</label>
	{#if yes}
		<p>
			Thank you. rất vui khi được đi cùng bạn
		</p>
	{:else}
		<p>
			Hãy cho tôi nghe ý kiến của bạn
		</p>
	{/if}
	<button disabled={!yes}>
		Let's go
	</button>
</main>

<style>
	p {
		color: purple;
		font-family: "Comic Sans MS", cursive;
		font-size: 2em;
	}
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>
