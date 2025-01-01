<script>
	export let name, text, index;
</script>

<div class="accordion-item">
	<h2 class="accordion-header" id="heading-{index}">
		<button
			class="accordion-button {index !== 0 ? 'collapsed' : ''} bg-dark text-white"
			type="button"
			data-bs-toggle="collapse"
			data-bs-target="#collapse-{index}"
			aria-expanded={index === 0 ? 'true' : 'false'}
			aria-controls="collapse-{index}"
		>
			<div class="d-flex w-100">
				<div class="flex-grow-1">{name}</div>
				<div><i class="bi bi-patch-plus-fill"></i></div>
			</div>
		</button>
	</h2>
	<div
		id="collapse-{index}"
		class="accordion-collapse collapse {index === 0 ? 'show' : ''}"
		aria-labelledby="heading-{index}"
		data-bs-parent="#accordionExample"
	>
		<div class="accordion-body text-white text-start">
			{text}
		</div>
	</div>
</div>

<style>
	.accordion-button::after {
		background-image: none;
	}

	.accordion-item {
		background-color: rgba(109, 109, 109, 0.403);
	}
</style>
