<script setup>
import Navbar from './components/Navbar.vue'
import Button from './components/Button.vue'
import Footer from './components/Footer.vue'
import Carousel from './components/Carousel.vue'
import OutfitFavsSection from './components/OutfitFavsSection.vue'
</script>

<template>
	<Navbar />
	<div class="h-screen relative flex justify-center overflow-hidden">
		<img src="/img/carousel/slide-1.png" alt="" class="hidden md:block" />
		<img src="/img/carousel/slide-mobile-1.png" alt="" class="md:hidden block" />
	</div>

	<OutfitFavsSection />

	<!-- banner -->
	<div class="w-full h-44 sm:h-56 md:h-72 lg:h-98 mb-5 mt-10 lg:my-20">
		<img src="/img/banner.png" alt="Banner Give it All" class="w-full h-full" />
	</div>

	<!-- ballling mens and womens -->
	<section
		class="grid grid-cols-1 gap-y-5 md:grid-cols-2 md:gap-x-4 sm:px-4 lg:gap-x-6 lg:px-6"
	>
		<div
			class="bg-mens bg-center md:bg-cover flex justify-center items-end w-full h-categorias"
		>
			<a href="/" class="mb-16">
				<Button styles="text-white border-white" />
			</a>
		</div>
		<div
			class="bg-womens bg-center md:bg-cover flex justify-center items-end w-full h-categorias"
		>
			<a href="/" class="mb-16">
				<Button styles="text-white border-white" />
			</a>
		</div>
	</section>

	<!-- franelas -->
	<section class="bg-white fle flex-col shadow-md px-3 py-2 mt-16" id="hamburguesas">
		<Carousel />
	</section>

	<Footer />
</template>
