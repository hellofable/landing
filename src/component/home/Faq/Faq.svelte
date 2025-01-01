<script>
	import Item from './Item.svelte';
	// Array of items
	let items = [
		{ name: 'Am I able to...', text: 'Whatever the answer is' },
		{ name: 'What about this...', text: 'This is the answer' },
		{ name: 'How does this work?', text: 'This is the explanation' },
		{ name: 'Can I do that?', text: 'Yes, you can.' },
		{ name: 'Why does this happen?', text: "Here's why." },
		{ name: 'What if...', text: 'It depends.' },
		{ name: 'Should I proceed?', text: 'Yes, but be careful.' },
		{ name: 'Is this correct?', text: 'It looks good!' },
		{ name: 'Can I modify it?', text: 'Absolutely.' },
		{ name: 'Does this apply?', text: 'Yes, it does.' }
	];
</script>

<div class="mx-3">
	<h3 class="mb-4">Frequently Asked Questions</h3>
	<div class="accordion" id="accordionExample">
		{#each items as { name, text }, index}
			<Item {name} {text} {index} />
		{/each}
	</div>
</div>

<style>
	.accordion {
		max-width: 58em;
		margin: auto;
		border: 0;
		outline: 0;

		--bs-accordion-border-color: none; /* Replace with your desired color */
	}
</style>
