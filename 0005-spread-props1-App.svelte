<script>

  import ProductCard from "./components/ProductCard.svelte";

  const productInfo = {
    product: "AI App",
    price: "5000 ₺",
    explanation: "AI app for Web3 dev",
    creator: "Mustafa Büyükdereli"
  }

</script>

<main>

  <ProductCard {...productInfo} />
 
</main>


<style>


</style>
