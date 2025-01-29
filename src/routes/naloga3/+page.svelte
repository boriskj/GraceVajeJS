<script lang="ts">
	// Napiši funkcijo, ki kot argument sprejme seznam števil in vrne nov seznam, ki vsebuje samo liha števila.
	let stevila: number[] = [10, 15, 20, 25, 30, 35];

	function filtrirajLiha(stevila: number[]) {
		let result = stevila.filter((stevilo) => stevilo % 2 !== 0);
		return result;
	}

	console.log(filtrirajLiha(stevila)); // Pričakovani rezultat: [15, 25, 35]
</script>

<code>
	<pre>// Napiši funkcijo, ki kot argument sprejme seznam števil in vrne nov seznam, ki vsebuje samo liha števila.</pre>
</code>
<hr />
<p class="text-xl">Celoten seznam: 10, 15, 20, 25, 30, 35</p>
<p class="text-xl">Filtiran seznam: {filtrirajLiha(stevila)}</p>
