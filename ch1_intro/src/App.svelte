<script>
	import Nested from "./nested.svelte";
	import Nesquik from "./nesquik.svelte";
	let name = 'svelte';
	let src = './images/dutti.png';
</script>

<h1>Hello {name}!</h1>

<img src={src} alt="smilemates" height="30%"/>

<p>Svelte Tutorials</p>
<Nested />
<Nesquik />


<style>
	/* Write your CSS here */
	p {
		color: purple;
		font-family: 'Comic Sans MS', cursive;
		font-size: 2em;
	}
</style>
