<script>
	import TopNav from '../topNav/TopNav.svelte';
	import LaptopImage from './LaptopImage.svelte';
	import WelcomeText from './WelcomeText.svelte';
	import Pricing from './Pricing.svelte';
	import SectionOne from './SectionOne.svelte';
	import SectionTwo from './SectionTwo.svelte';
	import SectionThree from './SectionThree.svelte';
	import Testimonials from './Testimonials/Testimonials.svelte';
	import Faq from './Faq/Faq.svelte';
</script>

<div class="wrapper mx-auto w-100 vh-100 overflow-y-scroll">
	<div class="cover-container w-100 p-3 mx-auto">
		<TopNav />
		<div style="height:50px;"></div>
		<WelcomeText />
		<div style="height:20px;"></div>

		<LaptopImage />
	</div>
	<div style="height:30px;"></div>
	<SectionOne />
	<SectionTwo />
	<div style="height:50px;"></div>
	<Testimonials />
	<div style="height:50px;"></div>
	<Pricing />
	<div style="height:50px;"></div>
	<SectionThree />
	<div style="height:70px;"></div>
	<Faq />
	<div style="height:150px;"></div>
</div>

<style>
	.wrapper {
		background-color: rgb(20, 10, 10);
		background-image: url('data:image/svg+xml;charset=utf8,%3Csvg%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%20viewBox%3D%220%200%20512%20512%22%20width%3D%22512%22%20height%3D%22512%22%20preserveAspectRatio%3D%22none%22%3E%20%3Cstyle%20type%3D%22text%2Fcss%22%3E%20path%20%7B%20fill%3A%20none%3B%20stroke%3A%20%23272733%3B%20stroke-width%3A%201.01px%3B%20stroke-linecap%3A%20round%3B%20stroke-linejoin%3A%20round%3B%20%7D%20%3C%2Fstyle%3E%20%3Cpath%20vector-effect%3D%22non-scaling-stroke%22%20d%3D%22M424%2C331.8c0%2C12.5-6.7%2C24.1-17.5%2C30.3l-132%2C76.2c-10.8%2C6.3-24.2%2C6.3-35%2C0l-132-76.2%20C96.7%2C355.8%2C90%2C344.3%2C90%2C331.8V179.2c0-12.5%2C6.7-24.1%2C17.5-30.3l132-76.2c10.8-6.3%2C24.2-6.3%2C35%2C0l132%2C76.2%20c10.8%2C6.3%2C17.5%2C17.8%2C17.5%2C30.3V331.8z%20M238.5%2C73l-256%2C147.6%20M273.5%2C439l252.1-145.4%20M256%2C634.7V378.3c0-12.5%2C6.7-24.1%2C17.5-30.3%20l252.1-145.4%20M256-122.7v256.4c0%2C12.5-6.7%2C24.1-17.5%2C30.3l-256%2C147.6%22%2F%3E%3C%2Fsvg%3E');
		font-family: 'Sora', serif;
		font-optical-sizing: auto;
	}

	.cover-container {
		max-width: 42em;
	}
</style>
