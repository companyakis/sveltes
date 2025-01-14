<script>

  import { year } from "./store";

  function yearMinusOne() {

    year.update(y => y - 1)
  }

</script>


<button on:click={yearMinusOne}>Year --</button>
