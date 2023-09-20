<script>
  import "../app.css";
  let name = "Thiago";
  let idade = 30;
  import imagePath from "$lib/images/mulher.png";
  import CoffeeScoreCard from "./CoffeeScoreCard.svelte";
</script>

<svelte:head>
  <title>Home</title>
  <meta name="description" content="Svelte demo app" />
</svelte:head>

<section>
  <CoffeeScoreCard />
</section>

<style>
  section {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    flex: 0.6;
  }
</style>
