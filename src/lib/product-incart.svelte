<script>
	import JumlahPesanan from '../lib/jumlah-pesanan.svelte';
</script>

<div class="flex items-center justify-between w-full h-24 border-b">
	<div class="flex items-center gap-3">
		<input type="checkbox" class="checkbox checkbox-sm checkbox-warning" />
		<div class=" bg-cover bg-center bg-[url('src/img/buah.png')] w-[95px] h-[95px]" />
		<div>
			<p class="font-['Dosis'] font-bold">Ayam Goreng</p>
			<div class="flex items-center gap-1 mt-2">
				<JumlahPesanan />
				×
				<p class="font-['Dosis']">Rp30.000</p>
			</div>
		</div>
	</div>
	<div class="p-2 duration-500 rounded-full cursor-pointer hover:bg-slate-50">
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
					d="M9.17065 4C9.58249 2.83481 10.6937 2 11.9999 2C13.3062 2 14.4174 2.83481 14.8292 4"
					stroke="#505258"
					stroke-width="1.5"
					stroke-linecap="round"
				/>
				<path d="M20.5 6H3.49988" stroke="#505258" stroke-width="1.5" stroke-linecap="round" />
				<path
					d="M18.3735 15.3991C18.1965 18.054 18.108 19.3815 17.243 20.1907C16.378 21 15.0476 21 12.3868 21H11.6134C8.9526 21 7.6222 21 6.75719 20.1907C5.89218 19.3815 5.80368 18.054 5.62669 15.3991L5.16675 8.5M18.8334 8.5L18.6334 11.5"
					stroke="#505258"
					stroke-width="1.5"
					stroke-linecap="round"
				/>
				<path d="M9.5 11L10 16" stroke="#505258" stroke-width="1.5" stroke-linecap="round" />
				<path d="M14.5 11L14 16" stroke="#505258" stroke-width="1.5" stroke-linecap="round" />
			</g></svg
		>
	</div>
</div>
