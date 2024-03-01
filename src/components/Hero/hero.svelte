<script>
  import Icons from "./icons.svelte";

  let src = "/avatar.jpg";
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
          Provident cupiditate voluptatem et in. Quaerat fugiat ut assumenda
          excepturi exercitationem quasi. In deleniti eaque aut repudiandae et a
          id nisi.
        </p>
        <Icons />
      </div>
    </div>
  </div>
</main>

<style>
</style>
