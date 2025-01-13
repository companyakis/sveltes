<script>
  let name = "Mustafa Büyükdereli";

  let year = 2025;

  function yearUp() {
    year++
  }

</script>

<main>

    <div class="name-info">{name}</div>

    <div class="year-info-area">
      <div class="year-text">{year}</div>
      <div class="button-div"><button class="year-button" on:click={yearUp}>Year ++</button></div>
    </div>

</main>

<style>

  .name-info {
    font-size: 50px;
    margin-bottom: 15px;
    color: blue;
    border: 1px solid green;
    padding: 10px;
    border-radius: 10px;
  }

  .year-info-area {
    display: flex;
    align-items: center;
    justify-content: space-around;
    border: 1px solid blue;
    padding: 10px;
    border-radius: 10px;
  }

  .year-text {
    font-size: 30px;
    color: purple;
  }

  .year-button {
    font-size: 20px;
    padding: 10px;
    border: none;
    background-color: purple;
    color: white;
    border-radius: 10px;
  }

</style>
