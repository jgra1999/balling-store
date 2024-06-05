<script setup>
import { ChevronLeftIcon, ChevronRightIcon } from '@heroicons/vue/24/outline'

import Navbar from './components/Navbar.vue'
import Button from './components/Button.vue'
import Footer from './components/Footer.vue'
</script>

<template>
	<Navbar />
	<div class="h-screen relative flex justify-center overflow-hidden">
		<img src="/img/carousel/slide-1.png" alt="" />
	</div>

	<p>
		Lorem ipsum, dolor sit amet consectetur adipisicing elit. Debitis aut doloribus
		explicabo deleniti nobis corporis provident? Id facilis, veniam excepturi aperiam
		ad cupiditate? Ratione nam assumenda quasi modi adipisci soluta! Soluta iste sit
		maiores ducimus dolore laborum, doloremque autem fugiat quis unde? In quia
		praesentium deleniti vitae! Quod, et nam! Vero veniam, rem deleniti maiores ullam
		molestias possimus officia nemo? Doloribus animi nisi quas, adipisci quo natus
		consectetur illum earum nostrum ratione pariatur corporis nihil minus quae
		recusandae. Quia consequatur nobis sunt dolor voluptatum. Itaque minima possimus
		sunt excepturi velit! Cum libero voluptate non dolorum ut. Repellat quo ratione
		aliquid quisquam error sed atque, consequatur autem dolor dicta vitae minima
		officiis obcaecati facilis porro, ipsa optio sunt assumenda totam accusamus.
		Eligendi velit minus, sequi nulla odio deserunt magni, ex minima tenetur quas
		voluptatem! Corrupti aliquam, totam sunt nisi animi laboriosam debitis voluptate
		perspiciatis? Corrupti quos quas accusamus fugit harum corporis. Ab, impedit nemo
		quia commodi quod blanditiis mollitia minima eum, repudiandae animi officiis
		explicabo tenetur iste ex sit inventore recusandae repellendus similique
		consequuntur quasi voluptatibus reiciendis placeat eos? Vel, aliquam? Nulla
		numquam tempora laborum qui doloremque expedita dolorum quo recusandae quam animi
		commodi debitis et excepturi sapiente, ad earum blanditiis voluptas architecto
		hic. Non a labore sequi libero eos quam? Dolorum modi expedita recusandae iste,
		aspernatur ut eius libero cupiditate dolores accusantium, autem voluptatibus
		voluptas perspiciatis magnam molestias unde quisquam! Mollitia, quam doloremque
		explicabo reiciendis assumenda harum laboriosam alias cum? Sunt, nostrum natus
		corrupti quam nulla beatae non earum facere repellendus nihil consequuntur
		pariatur perspiciatis incidunt corporis optio quos exercitationem sequi ducimus.
		Voluptatum, assumenda. Asperiores consequatur animi ipsam blanditiis ratione?
		Mollitia temporibus quasi neque optio, culpa ipsa quisquam quidem ea dignissimos
		architecto esse obcaecati hic debitis perferendis assumenda eaque quaerat a
		aliquam. In nostrum quas dolore nulla perferendis laudantium veritatis. Accusamus
		facilis vel delectus nesciunt? Temporibus sunt culpa voluptatem! Ipsa nobis illum
		corporis ipsam asperiores? Sed obcaecati, veniam quo voluptatem accusantium rem
		recusandae ratione officia deserunt veritatis cum sapiente quam. Quia ratione nam
		aut deleniti esse explicabo saepe rem error temporibus commodi iusto quas eum
		culpa harum magnam officia mollitia eos doloribus dicta earum assumenda,
		voluptates illo exercitationem cum. Rem! Sequi quia iste, atque praesentium omnis
		reprehenderit necessitatibus ad a, repellendus labore corrupti animi totam rerum
		laudantium, aliquid consectetur tempora repellat nemo asperiores? Ad commodi
		fugiat iusto, quaerat at accusantium. Blanditiis cum exercitationem saepe
		dolorem? Omnis dolorum modi qui rem distinctio ex inventore mollitia adipisci
		doloribus ad sequi expedita numquam corporis alias incidunt, voluptate neque.
		Facere at iure deleniti deserunt? Tempore sint quibusdam ipsam voluptate deleniti
		corporis ut dolore magni minus, rem ab voluptatibus optio reiciendis. In sunt
		accusamus maxime tempore maiores, facilis aliquam aut neque consequatur placeat
		quis odit. Dignissimos accusantium est veniam nemo odio explicabo velit nulla
		reiciendis quidem deserunt incidunt, voluptate autem fugiat dolore laudantium
		voluptatem nam aspernatur harum alias, porro quo, dolores non accusamus rerum?
		Ut? Facilis repellendus possimus eaque nostrum reiciendis, quisquam impedit ut
		voluptatibus maiores doloribus eius ratione aliquam inventore beatae? Obcaecati
		aperiam eaque eos tenetur impedit aspernatur amet iste nisi aut, asperiores
		exercitationem! Aperiam deleniti aut magni ipsa sit expedita eos beatae,
		cupiditate quo consequatur, a maxime quae at reiciendis rem. Rerum eius fugiat
		aliquid officia. Facilis adipisci odio nobis unde neque modi. Laboriosam pariatur
		tenetur ipsum nulla possimus labore ab soluta tempore architecto quas modi animi
		sit perspiciatis officia error deleniti, nobis in optio tempora. Totam iure quod,
		accusantium alias cupiditate aspernatur. Illo atque rem quod facilis illum
		dolorum consequuntur perspiciatis. Aliquid voluptatem eos quaerat inventore non
		ratione laudantium voluptatum assumenda quibusdam corporis? Repellendus odit
		rerum maiores, blanditiis fugiat cupiditate quam saepe?
	</p>

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
				<Button class="text-white" />
			</a>
		</div>
		<div
			class="bg-womens bg-center md:bg-cover flex justify-center items-end w-full h-categorias"
		>
			<a href="/" class="mb-16">
				<Button class="text-white" />
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
				<router-link to="#" class="text-gray-500 hover:text-black"
					>Ver todos</router-link
				>
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

		<!-- <div class="glider-contain relative">
				<div class="glider mt-10 overflow-hidden" id="">
					<card-products imageUrl="/img/prendas/prenda-1.png" name="short basic" price="12" />
					<card-products imageUrl="/img/prendas/prenda-2.png" name="Short Predator" price="10" />
					<card-products imageUrl="/img/prendas/prenda-3.png" name="Red Top" price="14" />
					<card-products imageUrl="/img/prendas/prenda-4.png" name="White Balling Set" price="10" />
					<card-products imageUrl="/img/prendas/prenda-5.png" name="Short Predator" price="10" />
				</div>
				<div role="tablist" class="dots my-10"></div>
			</div> -->
	</section>

	<Footer />
</template>
