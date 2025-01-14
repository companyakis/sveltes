<script>

  import { year } from "./store";

  function yearToInitial() {

    year.set(2025)
  }

</script>


<button on:click={yearToInitial}>Year Reset</button>
