<script>

    import { year } from "./store";

    function yearPlusOne() {

        year.update(y => y + 1)
    }

</script>


<button on:click={yearPlusOne}>Year ++</button>
