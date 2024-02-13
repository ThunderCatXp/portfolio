<script>
  import CardFuture from "./card_future.svelte";
  import CardOcupation from "./card_ocupation.svelte";
  import CardPassion from "./card_passion.svelte";
</script>

<main>
  <div class="hero min-h-screen bg-base-100">
    <div class="flex flex-row flex-wrap justify-center gap-7">
      <div><CardOcupation /></div>
      <div><CardPassion /></div>
      <div><CardFuture /></div>
    </div>
  </div>
</main>

<style>
</style>
