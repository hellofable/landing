<script>
	import Testimonial from './Testimonial.svelte';

	const testimonitals = [
		{ name: 'Rose (Canada)', text: "The design is minimal but that's what I like about it." },

		{ name: 'Faro (USA)', text: 'This is awesome!' },
		{ name: 'Kassie (L.A)', text: 'No learning curve. I opened it and was writing in seconds.' }
	];
</script>

<div class="row">
	{#each testimonitals as t}
		<Testimonial {t} />
	{/each}
</div>

<style>
	.row {
		max-width: 68em;
		margin: auto;
	}
</style>
