<script lang="ts">
	// Napiši funkcijo, ki preveri, ali je niz palindrom (se bere enako naprej in nazaj).
	let test1 = 'kajak';
	let test2 = 'banana';
	function jePalindrom(niz: string) {
		let ans = niz.split('').reverse().join('');
		return ans === niz;
	}
	console.log(jePalindrom(test1)); // Pričakovani rezultat: true
	console.log(jePalindrom(test2)); // Pričakovani rezultat: false
	console.log();
</script>

<code>
	<pre>// Napiši funkcijo, ki preveri, ali je niz palindrom (se bere enako naprej in nazaj).</pre>
</code>
<hr />
<p class="text-xl">ali je 'kajak' palindrom: {jePalindrom(test1)}</p>
<p class="text-xl">ali je 'ananas' palindrom: {jePalindrom(test2)}</p>
