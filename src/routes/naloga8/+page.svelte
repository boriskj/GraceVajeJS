<script lang="ts">
	// Napiši funkcijo, ki nariše piramido števil.

	function narisiPiramido(vrstice: number) {
		let vDolzina = 1;
		for (let i = 0; i < vrstice; i++) {
			// for i in range(5)
			let v: string = '';

			for (let j = 1; j <= vDolzina; j++) {
				//console.log(j);
				v += j + ' ';
			}
			vDolzina += 1;
			console.log(v);
		}
	}

	console.log(narisiPiramido(1000));

	/*
Izpis:
1 
1 2
1 2 3
1 2 3 4 
*/
</script>
