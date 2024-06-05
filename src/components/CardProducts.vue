<script setup>
import { ShoppingBagIcon, MagnifyingGlassIcon } from '@heroicons/vue/24/outline'

defineProps({
	name: String,
	imageUrl: String,
	styles: String,
	price: String
})
</script>

<template>
	<!--w-72 h-96  -->
	<div class="mx-3 relative group" :class="styles">
		<img :src="imageUrl" alt="" class="h-80 w-full" loading="lazy" />
		<div class="flex flex-col items-center mt-2 p-1" id="container">
			<div class="flex justify-between items-center w-full">
				<p class="capitalize font-semibold text-lg">{{ name }}</p>
				<span class="font-bold">{{ price }}$</span>
			</div>
			<div
				class="bg-white flex gap-x-8 rounded-full py-2 px-4 absolute bottom-16 lg:opacity-0 lg:group-hover:opacity-100 lg:bottom-0 lg:group-hover:bottom-20 transition-all duration-300 ease-in-out"
			>
				<MagnifyingGlassIcon class="w-5 h-5" />
				<ShoppingBagIcon class="w-5 h-5" />
			</div>
			<!-- TODO: hace que las opciones de ver y agregar en el carrito sean fijas en telefonos -->
		</div>
	</div>
</template>
