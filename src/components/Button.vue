<script setup>
defineProps({
	styles: String
})
</script>

<template>
	<div class="flex justify-start w-44 relative">
		<button
			class="py-1 px-4 text-2xl border-3 font-bold w-44 transform hover:-translate-y-1 hover:-translate-x-1 z-10 transition-transform duration-100"
			:class="styles"
		>
			Ver más
		</button>

		<div
			class="h-full w-full text-xl border-r-3 border-b-3 borderColor absolute"
			:class="styles"
		></div>
	</div>
</template>
