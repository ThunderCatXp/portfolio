<script>
  //

  import Card from "./card.svelte";

  // ==========================================

  let future = "/future.webp";
  let passion = "/passion.jpg";
  let occupation = "/ВЭК.jpg";

  // ==========================================

  // @ts-ignore
  import { t, locale, locales } from "i18n";

  // Create a locale specific timestamp
  $: time = new Date().toLocaleDateString($locale, {
    weekday: "long",
    year: "numeric",
    month: "long",
    day: "numeric",
  });
</script>

<main>
  <div class="hero min-h-screen bg-base-100">
    <div class="flex flex-row flex-wrap justify-center gap-7">
      <div>
        <Card
          src={occupation}
          title={$t("occupation")}
          text={$t("card.occupation")}
        />
      </div>
      <div>
        <Card src={passion} title={$t("passion")} text={$t("card.passion")} />
      </div>
      <div>
        <Card src={future} title={$t("future")} text={$t("card.future")} />
      </div>
    </div>
  </div>
</main>

<style>
</style>
