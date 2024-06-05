<script setup>
import { ChevronLeftIcon, ChevronRightIcon } from '@heroicons/vue/24/outline'

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
		<div
			class="flex justify-between items-center border-b-2 border-t-2 border-gray-400 lg:px-4 py-2"
		>
			<div class="font-semibold text-lg sm:text-xl flex gap-x-4">
				<h2>Prendas Nuevas</h2>
				<a to="#" class="text-gray-500 hover:text-black">Ver todos</a>
			</div>

			<div class="flex">
				<button>
					<ChevronLeftIcon
						class="w-7 h-7 sm:w-8 sm:h-8 active:text-primary lg:hover:text-primary left-arrow"
					/>
				</button>
				<button>
					<ChevronRightIcon
						class="w-7 h-7 sm:w-8 sm:h-8 active:text-primary lg:hover:text-primary right-arrow"
					/>
				</button>
			</div>
		</div>

		<Carousel title="Slide de Prueba" />
	</section>

	<Footer />
</template>
