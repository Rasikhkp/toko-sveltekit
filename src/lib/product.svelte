<script>
	import { fly } from 'svelte/transition';
	import JumlahPesanan from './jumlah-pesanan.svelte';

	export let namaProduk, kategori, harga, gambarProduk;
</script>

<div class="py-5 bg-white shadow-[0_0_0_1px] shadow-gray-300">
	<div class="mx-auto bg-cover bg-center bg-[url('src/img/{gambarProduk}')] w-52 h-52" />

	<div class="text-sm text-center text-gray-400 font-['Inter'] mt-2">{kategori}</div>
	<div class="font-['Dosis'] text-center font-semibold">{namaProduk}</div>
	<div class="w-40 mx-auto my-2 border" />
	<div class="text-sm text-center text-gray-400 font-['Inter']">{harga}</div>

	<div class="flex w-40 gap-2 mx-auto mt-3">
		<JumlahPesanan />
		<button
			class="w-10 relative h-11 flex justify-center items-center hover:bg-[#9cad57] rounded bg-[#96B416]"
		>
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
		</button>
	</div>
</div>
