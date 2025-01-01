<script>
	import image from './images/man-standing.svg';
</script>

<div class="wrapper">
	<div class="container d-flex align-items-center">
		<div class="row w-100">
			<!-- Image Column -->
			<div class="col-lg-6 d-flex align-items-center justify-content-center order-lg-1 order-2">
				<div
					class="about-image text-center mt-50 wow fadeInRightBig"
					data-wow-duration="1s"
					data-wow-delay="0.5s"
				>
					<img class="girl img-fluid" src={image} alt="about" />
				</div>
			</div>

			<!-- Text Column -->
			<div
				class="col-sm-6 col-md-6 col-lg-6 col-10 d-flex align-items-center order-lg-2 order-1 m-auto"
			>
				<div
					class="about-content mt-50 wow fadeInLeftBig"
					data-wow-duration="1s"
					data-wow-delay="0.5s"
				>
					<div class="section-title">
						<div class="line"></div>
						<h3 class="title">
							realtime
							<span class="orange-text">collaboration</span>
						</h3>
					</div>
					<p class="text">
						Work together seamlessly in <span class="text-white-50">real-time</span> with your team,
						no matter where they are. Share your script and get instant feedback, make edits, and
						brainstorm ideas—<span class="text-white-50">everything stays in sync.</span>
					</p>
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
		height: 310px;
	}

	.wrapper {
		background: rgba(47, 43, 43, 0.618);
		padding: 0 0 20px 0;
	}
</style>
