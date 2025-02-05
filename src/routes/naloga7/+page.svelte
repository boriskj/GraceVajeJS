<script lang="ts">
	function filtrirajDeljiva(s: number[]) {
		return s.filter((b) => b % 3 === 0 || b % 5 === 0);
		//return s.filter((h) => h % 5 === 0);
	}

	const stevila: number[] = [1, 3, 5, 7, 10, 15, 22, 30];
	console.log(filtrirajDeljiva(stevila));
	// Pričakovan rezultat [3, 5, 10, 15, 30]
</script>
