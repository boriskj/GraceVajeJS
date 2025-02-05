<script lang="ts">
	// Napiši funkcijo, ki vrne preveri besedo in vrne slovar z vsemi črkami in število pojavitev.
	function steviloPojavitev(beseda: string) {
		let rezultat: Record<string, number> = {};

		beseda.split('').forEach((crka) => {
			if (crka in rezultat) {
				rezultat[crka] = rezultat[crka] + 1;
			} else {
				rezultat[crka] = 1;
			}
		});

		return rezultat;
	}

	console.log(steviloPojavitev('Boris')); // ["b", "a", "n", "a", ...]
	// Pričakovani rezultat: { b: 1, a: 3, n: 2 }
</script>

<code
	><pre>
  // Napiši funkcijo, ki vrne preveri besedo in vrne slovar z vsemi črkami in število pojavitev.
</pre></code
>
<hr />
<p class="text-xl">Za testiranje odpri konzolo.</p>
