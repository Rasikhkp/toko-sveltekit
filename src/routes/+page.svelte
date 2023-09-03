<script>
	import Product from '../lib/product.svelte';
	// let;
</script>

<svelte:head>
	<style>
		/* Hide the up and down arrows for input type number */
		input[type='number']::-webkit-inner-spin-button,
		input[type='number']::-webkit-outer-spin-button {
			-webkit-appearance: none;
			margin: 0;
		}
	</style>
</svelte:head>

<div class="w-[600px]">
	<nav class="flex justify-between p-5 h-[62px] items-center bg-[#96B416] gap-5">
		<div>
			<svg
				fill="#ffffff"
				height="35px"
				width="35px"
				version="1.1"
				id="Layer_1"
				xmlns="http://www.w3.org/2000/svg"
				xmlns:xlink="http://www.w3.org/1999/xlink"
				viewBox="0 0 512 512"
				xml:space="preserve"
				stroke="#ffffff"
				><g id="SVGRepo_bgCarrier" stroke-width="0" /><g
					id="SVGRepo_tracerCarrier"
					stroke-linecap="round"
					stroke-linejoin="round"
				/><g id="SVGRepo_iconCarrier">
					<g>
						<g>
							<path
								d="M495.304,278.261h-61.217v-50.087c0-27.618-22.469-50.087-50.087-50.087s-50.087,22.469-50.087,50.087v50.087h-33.391 V104.587c23.934,12.27,53.408,7.54,72.348-12.548c38,40.306,105.739,13.141,105.739-41.951V16.696 c0-9.22-7.475-16.696-16.696-16.696C442.656,0,34.642,0,16.696,0C7.475,0,0,7.475,0,16.696v33.391 c0,23.738,13.59,44.349,33.391,54.5v173.674H16.696C7.475,278.261,0,285.736,0,294.957v133.565c0,9.22,7.475,16.696,16.696,16.696 h51.767C76.218,483.275,109.948,512,150.261,512c40.313,0,74.042-28.725,81.799-66.783h101.853v50.087 c0,9.22,7.475,16.696,16.696,16.696s16.696-7.475,16.696-16.696v-50.087h50.087c9.22,0,16.696-7.475,16.696-16.696v-116.87h61.217 c9.22,0,16.696-7.475,16.696-16.696S504.525,278.261,495.304,278.261z M389.565,33.391h55.652v16.696 c0,15.343-12.483,27.826-27.826,27.826s-27.826-12.483-27.826-27.826V33.391z M300.522,33.391h55.652v16.696 c0,15.343-12.483,27.826-27.826,27.826s-27.826-12.483-27.826-27.826V33.391z M211.478,33.391h55.652v16.696 c0,15.343-12.483,27.826-27.826,27.826c-15.343,0-27.826-12.483-27.826-27.826V33.391z M122.435,33.391h55.652v16.696 c0,15.343-12.483,27.826-27.826,27.826s-27.826-12.483-27.826-27.826V33.391z M105.739,92.038 c24.218,25.688,64.821,25.691,89.043,0c18.926,20.075,48.397,24.828,72.348,12.548v173.675h-33.391c0-7.672,0-59.585,0-66.783 c0-36.824-29.959-66.783-66.783-66.783s-66.783,29.959-66.783,66.783c0,7.312,0,58.286,0,66.783H66.783V111.039 C82.081,109.654,95.765,102.617,105.739,92.038z M133.565,211.478c0-18.412,14.979-33.391,33.391-33.391 c18.412,0,33.391,14.979,33.391,33.391H133.565z M200.348,244.87v33.391h-66.783V244.87H200.348z M33.391,33.391h55.652v16.696 c0,15.343-12.483,27.826-27.826,27.826S33.391,65.43,33.391,50.087V33.391z M150.261,478.609 c-27.618,0-50.087-22.469-50.087-50.087s22.469-50.087,50.087-50.087c27.618,0,50.087,22.469,50.087,50.087 S177.879,478.609,150.261,478.609z M400.696,411.826H232.06c-7.756-38.057-41.485-66.783-81.799-66.783 c-40.313,0-74.042,28.725-81.799,66.783H33.391V311.652c13.04,0,354.085,0,367.304,0V411.826z M400.696,278.261h-33.391v-50.087 c0-9.206,7.49-16.696,16.696-16.696s16.696,7.49,16.696,16.696V278.261z"
							/>
						</g>
					</g> <g> <g> <circle cx="150.261" cy="428.522" r="16.696" /> </g> </g>
				</g></svg
			>
		</div>
		<div class="flex items-center justify-center gap-7">
			<div>
				<svg
					width="23px"
					height="23px"
					viewBox="0 0 24 24"
					fill="none"
					xmlns="http://www.w3.org/2000/svg"
					><g id="SVGRepo_bgCarrier" stroke-width="0" /><g
						id="SVGRepo_tracerCarrier"
						stroke-linecap="round"
						stroke-linejoin="round"
					/><g id="SVGRepo_iconCarrier">
						<path
							d="M15.7955 15.8111L21 21M18 10.5C18 14.6421 14.6421 18 10.5 18C6.35786 18 3 14.6421 3 10.5C3 6.35786 6.35786 3 10.5 3C14.6421 3 18 6.35786 18 10.5Z"
							stroke="#ffffff"
							stroke-width="2"
							stroke-linecap="round"
							stroke-linejoin="round"
						/>
					</g></svg
				>
			</div>
			<div>
				<svg
					width="23px"
					height="23px"
					viewBox="0 0 24 24"
					fill="none"
					xmlns="http://www.w3.org/2000/svg"
					><g id="SVGRepo_bgCarrier" stroke-width="0" /><g
						id="SVGRepo_tracerCarrier"
						stroke-linecap="round"
						stroke-linejoin="round"
					/><g id="SVGRepo_iconCarrier">
						<path
							d="M20.2236 12.5257C19.6384 9.40452 19.3458 7.84393 18.2349 6.92196C17.124 6 15.5362 6 12.3606 6H11.6394C8.46386 6 6.87608 6 5.76518 6.92196C4.65428 7.84393 4.36167 9.40452 3.77645 12.5257C2.95353 16.9146 2.54207 19.1091 3.74169 20.5545C4.94131 22 7.17402 22 11.6394 22H12.3606C16.826 22 19.0587 22 20.2584 20.5545C20.9543 19.7159 21.108 18.6252 20.9537 17"
							stroke="#ffffff"
							stroke-width="1.5"
							stroke-linecap="round"
						/>
						<path
							d="M9 6V5C9 3.34315 10.3431 2 12 2C13.6569 2 15 3.34315 15 5V6"
							stroke="#ffffff"
							stroke-width="1.5"
							stroke-linecap="round"
						/>
					</g></svg
				>
			</div>
		</div>
	</nav>

	<main class="my-10">
		<div
			class="grid grid-cols-2 gap-[1px] mx-5 overflow-hidden shadow-[0_0_0_1px] shadow-gray-300 rounded-lg"
		>
			<Product
				namaProduk="Tempe Goreng"
				gambarProduk="makanan1.jpg"
				harga="Rp30.000"
				kategori="Makanan"
			/>
			<Product
				namaProduk="Tempe Goreng"
				gambarProduk="makanan2.jpg"
				harga="Rp30.000"
				kategori="Makanan"
			/>
			<Product
				namaProduk="Tempe Goreng"
				gambarProduk="makanan3.jpg"
				harga="Rp30.000"
				kategori="Makanan"
			/>
			<Product
				namaProduk="Tempe Goreng"
				gambarProduk="makanan4.jpg"
				harga="Rp30.000"
				kategori="Makanan"
			/>
			<Product
				namaProduk="Tempe Goreng"
				gambarProduk="buah.png"
				harga="Rp30.000"
				kategori="Makanan"
			/>
			<Product
				namaProduk="Tempe Goreng"
				gambarProduk="makanan4.jpg"
				harga="Rp30.000"
				kategori="Makanan"
			/>
			<Product
				namaProduk="Tempe Goreng"
				gambarProduk="makanan3.jpg"
				harga="Rp30.000"
				kategori="Makanan"
			/>
			<Product
				namaProduk="Tempe Goreng"
				gambarProduk="makanan2.jpg"
				harga="Rp30.000"
				kategori="Makanan"
			/>
			<Product
				namaProduk="Tempe Goreng"
				gambarProduk="makanan1.jpg"
				harga="Rp30.000"
				kategori="Makanan"
			/>
			<Product
				namaProduk="Tempe Goreng"
				gambarProduk="buah.png"
				harga="Rp30.000"
				kategori="Makanan"
			/>
			<Product
				namaProduk="Tempe Goreng"
				gambarProduk="buah.png"
				harga="Rp30.000"
				kategori="Makanan"
			/>
		</div>
	</main>
</div>
