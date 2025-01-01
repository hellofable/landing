<script>
	export let t;
</script>

<div class="col-lg-4 col-md-4 col-sm-4 col-8 m-auto">
	<hgroup class="speech-bubble">
		<div class="text">{t.text}</div>
		<div class="name">{t.name}</div>
	</hgroup>
</div>

<style>
	.text {
		font-size: 20px;
		font-style: italic;
	}
	.name {
		font-size: 14px;
	}
	.speech-bubble {
		position: relative;
		background: #0f3264;
		border-radius: 0.4em;
		padding: 20px;
		margin-bottom: 50px;
	}

	.speech-bubble:after {
		content: '';
		position: absolute;
		bottom: 0;
		left: 50%;
		width: 0;
		height: 0;
		border: 36px solid transparent;
		border-top-color: #0f3264;
		border-bottom: 0;
		border-left: 0;
		margin-left: -48px;
		margin-bottom: -36px;
	}
</style>
