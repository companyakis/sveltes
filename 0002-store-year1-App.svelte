<script>

  import Yearup from "./Yearup.svelte";
  import Yeardown from "./Yeardown.svelte";
  import Yearreset from "./Yearreset.svelte";

  import { year } from "./store";

</script>

<main>

<div class="year-info">Year: {$year}</div>

<div>
  <Yearup />
  <Yeardown />
  <Yearreset />
</div>

</main>

<style>

  .year-info {
    font-size: 35px;
    margin-bottom: 10px;
    color: purple;
  }


</style>
