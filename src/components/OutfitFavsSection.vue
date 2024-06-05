<script setup>
import Button from './Button.vue'
import { onMounted } from 'vue'

onMounted(() => {
	const carousel = document.getElementById('container__carousel')

	setInterval(() => {
		carousel.scrollLeft += carousel.scrollLeft = 2
	}, 50)
})
</script>

<template>
	<!-- Outfits favs -->
	<section
		class="flex flex-col md:flex-row md:justify-between md:items-center mt-5 md:my-20"
	>
		<div
			class="flex flex-col items-center text-center md:mx-5 lg:mx-20 bg-white order-2 md:order-1"
		>
			<h2 class="capitalize text-4xl md:text-5xl mt-10 mb-4 w-96">
				Nuestros outfits favoritos
			</h2>
			<Button styles="text-black border-black" />
		</div>

		<div
			class="flex relative overflow-hidden order-1 md:order-2"
			id="container__carousel"
		>
			<div>
				<div class="flex flex-nowrap md:gap-x-2">
					<div class="h-outfits w-96">
						<img
							src="/img/outfits/outfit-1.jpg"
							loading="lazy"
							alt="imagen outfit 1"
						/>
					</div>
					<div class="h-outfits w-96">
						<img
							src="/img/outfits/outfit-2.jpg"
							loading="lazy"
							alt="imagen outfit 2"
						/>
					</div>
					<div class="h-outfits w-96">
						<img
							src="/img/outfits/outfit-3.jpg"
							loading="lazy"
							alt="imagen outfit 3"
						/>
					</div>
					<div class="h-outfits w-96">
						<img
							src="/img/outfits/outfit-4.jpg"
							loading="lazy"
							alt="imagen outfit 4"
						/>
					</div>
					<div class="h-outfits w-96">
						<img
							src="/img/outfits/outfit-5.jpg"
							loading="lazy"
							alt="imagen outfit 5"
						/>
					</div>
					<div class="h-outfits w-96">
						<img
							src="/img/outfits/outfit-6.jpg"
							loading="lazy"
							alt="imagen outfit 1"
						/>
					</div>
					<div class="h-outfits w-96">
						<img
							src="/img/outfits/outfit-7.jpg"
							loading="lazy"
							alt="imagen outfit 2"
						/>
					</div>
					<div class="h-outfits w-96">
						<img
							src="/img/outfits/outfit-8.jpg"
							loading="lazy"
							alt="imagen outfit 3"
						/>
					</div>
					<div class="h-outfits w-96">
						<img
							src="/img/outfits/outfit-9.jpg"
							loading="lazy"
							alt="imagen outfit 4"
						/>
					</div>
					<div class="h-outfits w-96">
						<img
							src="/img/outfits/outfit-10.jpg"
							loading="lazy"
							alt="imagen outfit 5"
						/>
					</div>
					<div class="h-outfits w-96">
						<img
							src="/img/outfits/outfit-11.jpg"
							loading="lazy"
							alt="imagen outfit 1"
						/>
					</div>
					<div class="h-outfits w-96">
						<img
							src="/img/outfits/outfit-1.jpg"
							loading="lazy"
							alt="imagen outfit 1"
						/>
					</div>
					<div class="h-outfits w-96">
						<img
							src="/img/outfits/outfit-2.jpg"
							loading="lazy"
							alt="imagen outfit 2"
						/>
					</div>
					<div class="h-outfits w-96">
						<img
							src="/img/outfits/outfit-3.jpg"
							loading="lazy"
							alt="imagen outfit 3"
						/>
					</div>
					<div class="h-outfits w-96">
						<img
							src="/img/outfits/outfit-4.jpg"
							loading="lazy"
							alt="imagen outfit 4"
						/>
					</div>
					<div class="h-outfits w-96">
						<img
							src="/img/outfits/outfit-5.jpg"
							loading="lazy"
							alt="imagen outfit 5"
						/>
					</div>
					<div class="h-outfits w-96">
						<img
							src="/img/outfits/outfit-6.jpg"
							loading="lazy"
							alt="imagen outfit 1"
						/>
					</div>
					<div class="h-outfits w-96">
						<img
							src="/img/outfits/outfit-7.jpg"
							loading="lazy"
							alt="imagen outfit 2"
						/>
					</div>
					<div class="h-outfits w-96">
						<img
							src="/img/outfits/outfit-8.jpg"
							loading="lazy"
							alt="imagen outfit 3"
						/>
					</div>
					<div class="h-outfits w-96">
						<img
							src="/img/outfits/outfit-9.jpg"
							loading="lazy"
							alt="imagen outfit 4"
						/>
					</div>
					<div class="h-outfits w-96">
						<img
							src="/img/outfits/outfit-10.jpg"
							loading="lazy"
							alt="imagen outfit 5"
						/>
					</div>
					<div class="h-outfits w-96">
						<img
							src="/img/outfits/outfit-11.jpg"
							loading="lazy"
							alt="imagen outfit 1"
						/>
					</div>
					<div class="h-outfits w-96">
						<img
							src="/img/outfits/outfit-1.jpg"
							loading="lazy"
							alt="imagen outfit 1"
						/>
					</div>
					<div class="h-outfits w-96">
						<img
							src="/img/outfits/outfit-2.jpg"
							loading="lazy"
							alt="imagen outfit 2"
						/>
					</div>
					<div class="h-outfits w-96">
						<img
							src="/img/outfits/outfit-3.jpg"
							loading="lazy"
							alt="imagen outfit 3"
						/>
					</div>
					<div class="h-outfits w-96">
						<img
							src="/img/outfits/outfit-4.jpg"
							loading="lazy"
							alt="imagen outfit 4"
						/>
					</div>
					<div class="h-outfits w-96">
						<img
							src="/img/outfits/outfit-5.jpg"
							loading="lazy"
							alt="imagen outfit 5"
						/>
					</div>
					<div class="h-outfits w-96">
						<img
							src="/img/outfits/outfit-6.jpg"
							loading="lazy"
							alt="imagen outfit 1"
						/>
					</div>
					<div class="h-outfits w-96">
						<img
							src="/img/outfits/outfit-7.jpg"
							loading="lazy"
							alt="imagen outfit 2"
						/>
					</div>
					<div class="h-outfits w-96">
						<img
							src="/img/outfits/outfit-8.jpg"
							loading="lazy"
							alt="imagen outfit 3"
						/>
					</div>
					<div class="h-outfits w-96">
						<img
							src="/img/outfits/outfit-9.jpg"
							loading="lazy"
							alt="imagen outfit 4"
						/>
					</div>
					<div class="h-outfits w-96">
						<img
							src="/img/outfits/outfit-10.jpg"
							loading="lazy"
							alt="imagen outfit 5"
						/>
					</div>
					<div class="h-outfits w-96">
						<img
							src="/img/outfits/outfit-11.jpg"
							loading="lazy"
							alt="imagen outfit 1"
						/>
					</div>
				</div>
			</div>
		</div>
	</section>
</template>
