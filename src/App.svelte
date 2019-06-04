<script>
	let name = 'Andrew';
	let age = 32;

	function incAge () {
		age += 1;
	}
</script>

<style>

	h1 {
		color: purple;
	}

</style>

<h1>Hello {name}!</h1>
<h1>My age is {age}</h1>
<button on:click={incAge}> Change Age  </button>