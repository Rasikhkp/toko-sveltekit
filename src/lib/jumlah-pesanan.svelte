<script>
	let jumlahPesanan = 1;
	function increment() {
		jumlahPesanan++;
		console.log('terklik increment');
	}

	function decrement() {
		if (jumlahPesanan == 1) {
			jumlahPesanan = 1;
		} else {
			jumlahPesanan--;
		}

		console.log('terklik decrement');
	}
</script>

<div class="w-28 h-[45px] border flex justify-between items-center border-gray-300">
	<button on:click={decrement} class="flex items-center justify-center w-10 h-full">-</button>
	<input
		type="number"
		bind:value={jumlahPesanan}
		class="w-full h-full text-center focus:border-0 focus:outline-none"
	/>
	<button on:click={increment} class="flex items-center justify-center w-10 h-full">+</button>
</div>
