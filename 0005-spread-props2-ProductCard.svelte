<script>
    export let product
    export let price
    export let explanation
    export let creator
</script>

<div class="card">

    <h1>Product name: {product}</h1>

    <h3>Price: {price}</h3>

    <h4>Product info: {explanation}</h4>

    <h3>Product owner: {creator}</h3>

</div>

<style>

    .card {

        width: 500px;
        height: 200px;
        border: none;
        background-color: blueviolet;
        color: rgb(226, 233, 233);
        text-align: center;
        padding: 10px;
        border-radius: 10px;
    }


</style>
