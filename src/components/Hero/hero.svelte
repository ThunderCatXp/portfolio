<script>
  import Icons from "./icons.svelte";

  let src = "/avatar.jpg";

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
    <div class="hero-content flex-col lg:flex-row-reverse">
      <img
        {src}
        class="max-w-sm rounded-lg shadow-2xl object-cover"
        alt="ThunderCat's avatar"
      />
      <div>
        <h1 class="text-5xl font-bold">ThunderCat</h1>
        <p class="py-6 text-balance">
          {$t("homepage.info")}
        </p>
        <Icons />
      </div>
    </div>
  </div>
</main>

<style scoped>
  img:hover {
    transform: scale(1.02);
  }
</style>
