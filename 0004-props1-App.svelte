<script>

  import CounterScreen from "./components/CounterScreen.svelte";

  let counter = 0

  function counterUp() {
    counter++
  }

  function counterDown() {
    counter--
  }

</script>

<main>

  <CounterScreen {counter} />

  <div>
    <button on:click={counterUp}>Counter ++</button>

    <button on:click={counterDown}>Counter --</button>
  </div>

</main>


<style>


</style>
