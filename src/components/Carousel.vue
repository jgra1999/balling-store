<script setup>
import emblaCarouselVue from 'embla-carousel-vue'
import CardProducts from './CardProducts.vue'

const [emblaRef, emblaApi] = emblaCarouselVue({ loop: true })
</script>

<template>
	<div class="embla mt-5" ref="emblaRef">
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
