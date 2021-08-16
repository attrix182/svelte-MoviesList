<script lang="ts">

  let value = ''

  const handleInput = (event) => 
  value = event.target.value

</script>



<input value={value} on:input={handleInput}>

<style>
	
</style>