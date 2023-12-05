<script>
  export let page = "page";

  const onSayHi = () => {
    alert("Hi!");
  };
</script>

<style>
  h1 {
    color: red;
  }
</style>

<h1>{page}</h1>
<button on:click={onSayHi}>Say Hi!</button>