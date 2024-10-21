<script>
  export let src = "";
  export let title = "";
  export let text = "";
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
      <h2 class="card-title font-bold">{title}</h2>
      <p>{@html text}</p>
    </div>
  </div>
</main>

<style>
</style>
