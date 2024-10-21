<script>
  let src = "/passion.jpg";

  // @ts-ignore
  import { t, locale, locales } from "i18n";

  // Create a locale specific timestamp
  // @ts-ignore
  $: time = new Date().toLocaleDateString($locale, {
    weekday: "long",
    year: "numeric",
    month: "long",
    day: "numeric",
  });
</script>

<main>
  <div class="card w-[24rem] bg-base-200 shadow-xl">
    <figure class="px-10 pt-10">
      <img
        {src}
        alt=""
        class="rounded-xl aspect-square object-cover"
        loading="lazy"
      />
    </figure>
    <div class="card-body items-center text-center">
      <h2 class="card-title font-bold">{@html $t("passion")}</h2>
      <p>{@html $t("card.passion")}</p>
    </div>
  </div>
</main>

<style>
</style>
