<script>
  let value = "";

  const handleInput = (event) => { value = event.target.value; };

  console.log(value);

</script>

<input {value} on:input={handleInput} />
