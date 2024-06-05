<script setup>
import { ChevronLeftIcon, ChevronRightIcon } from '@heroicons/vue/24/outline'
import emblaCarouselVue from 'embla-carousel-vue'
import CardProducts from './CardProducts.vue'

const [emblaRef, emblaApi] = emblaCarouselVue({ loop: true })
</script>

<template>
	<div
		class="flex justify-between items-center border-b-2 border-t-2 border-gray-400 lg:px-4 py-2"
	>
		<div class="font-semibold text-lg sm:text-xl flex gap-x-4">
			<h2>Prendas Nuevas</h2>
			<a to="#" class="text-gray-500 hover:text-black">Ver todos</a>
		</div>

		<div class="flex">
			<button class="embla__prev">
				<ChevronLeftIcon
					class="w-7 h-7 sm:w-8 sm:h-8 active:text-primary lg:hover:text-primary left-arrow"
				/>
			</button>
			<button class="embla__next">
				<ChevronRightIcon
					class="w-7 h-7 sm:w-8 sm:h-8 active:text-primary lg:hover:text-primary right-arrow"
				/>
			</button>
		</div>
	</div>

	<div class="embla mt-5" ref="emblaRef">
		<div class="embla__viewport">
			<div class="embla__container">
				<CardProducts
					styles="embla__slide"
					imageUrl="/img/prendas/prenda-1.png"
					name="short basic"
					price="12"
				/>
				<CardProducts
					styles="embla__slide"
					imageUrl="/img/prendas/prenda-2.png"
					name="Short Predator"
					price="10"
				/>

				<CardProducts
					styles="embla__slide"
					imageUrl="/img/prendas/prenda-3.png"
					name="Red Top"
					price="14"
				/>

				<CardProducts
					styles="embla__slide"
					imageUrl="/img/prendas/prenda-4.png"
					name="White Balling Set"
					price="10"
				/>

				<CardProducts
					styles="embla__slide"
					imageUrl="/img/prendas/prenda-5.png"
					name="Short Predator"
					price="10"
				/>
			</div>
		</div>
	</div>
</template>

<style scoped>
.embla {
	overflow: hidden;
}
.embla__container {
	display: flex;
}
.embla__slide {
	flex: 0 0 20%;
	height: 384px;
	min-width: 0;
}
@media (max-width: 640px) {
	.embla__slide {
		flex: 0 0 85%; /* Breakpoint SM slide covers 50% of the viewport */
	}
}
</style>
