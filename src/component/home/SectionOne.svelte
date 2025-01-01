<script>
	import image from './images/girl-couch.svg';
</script>

<div class="wrapper">
	<div class="container d-flex align-items-center">
		<div class="row w-100">
			<!-- Text Content Column -->
			<div class="col-sm-6 col-md-6 col-lg-6 col-10 d-flex align-items-center m-auto">
				<div
					class="about-content mt-50 wow fadeInLeftBig"
					data-wow-duration="1s"
					data-wow-delay="0.5s"
				>
					<div class="section-title">
						<div class="line"></div>
						<h3 class="title">
							<span class="orange-text">cards first</span>
							approach to screenwriting
						</h3>
					</div>
					<p class="text">
						For years writers have been using <span class="text-white-50">index cards</span> to map
						out their stories. At Fable, we've taken the cards method to heart and made it the
						<span class="text-white-50"> core of our writing platform.</span>
					</p>
				</div>
			</div>

			<!-- Image Column -->
			<div class="col-lg-6 d-flex align-items-center justify-content-center">
				<div
					class="about-image text-center mt-50 wow fadeInRightBig"
					data-wow-duration="1s"
					data-wow-delay="0.5s"
				>
					<img class="girl img-fluid" src={image} alt="about" />
				</div>
			</div>
		</div>
	</div>
</div>

<style>
	.container {
		max-width: 52em;
	}
	img.girl {
		height: 280px;
	}

	.wrapper {
		background: rgba(47, 43, 43, 0.618);
		padding: 20px 0;
	}
</style>
