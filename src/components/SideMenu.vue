<script setup>
import { XMarkIcon, Bars3Icon } from '@heroicons/vue/24/outline'

function hideMenu() {
	const sidebar = document.getElementById('sidebar')
	const options = document.getElementById('options')
	const background = document.getElementById('background')

	options.classList.add('-translate-x-full')
	background.classList.remove('opacity-75')

	setTimeout(() => {
		sidebar.classList.remove('flex')
		sidebar.classList.add('hidden')
	}, 200)
}

function showMenu() {
	const sidebar = document.getElementById('sidebar')
	const options = document.getElementById('options')
	const background = document.getElementById('background')

	sidebar.classList.remove('hidden')
	sidebar.classList.add('flex')

	setTimeout(() => {
		options.classList.remove('-translate-x-full')
		background.classList.add('opacity-75')
	}, 100)
}
</script>

<template>
	<button @click="showMenu" class="transition-opacity duration-700">
		<Bars3Icon class="w-8 h-8 active:text-white" />
	</button>
	<div class="fixed z-30 top-0 left-0 w-screen h-screen hidden" id="sidebar">
		<div
			class="flex flex-col bg-primary w-3/4 h-screen opacity-100 p-4 transform translate -translate-x-full transition-transform duration-200"
			id="options"
		>
			<div class="flex justify-between items-center">
				<button @click="hideMenu">
					<XMarkIcon class="w-10 h-10 text-white" />
				</button>
				<img src="/img/logo.png" alt="logo flow" loading="lazy" class="w-8" />
			</div>
			<ul
				class="fle flex-col divide-y-2 divide-gray-200 mt-8 text-white"
				@click="hideMenu"
			>
				<li class="py-3">
					<a href="#" class="font-bold text-xl">Home</a>
				</li>
				<li class="py-3">
					<a href="#" class="font-bold text-xl">Hombres</a>
				</li>
				<li class="py-3">
					<a href="#" class="font-bold text-xl">Mujeres</a>
				</li>
				<li class="py-3">
					<a href="#" class="font-bold text-xl">Contáctenos</a>
				</li>
			</ul>
		</div>
		<div
			class="bg-black opacity-0 transition-opacity duration-100 w-1/4 h-screen"
			id="background"
		></div>
	</div>
</template>
