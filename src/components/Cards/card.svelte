<script>
  // @ts-nocheck

  export let src = "";
  export let title = "";
  export let text = "";
  import svelteTilt from "vanilla-tilt-svelte";
</script>

<main>
  <div
    class="card w-[24rem] bg-base-200 shadow-xl"
    use:svelteTilt={{
      reverse: false,
      max: 5,
      startX: 0,
      startY: 0,
      perspective: 1000,
      scale: 1,
      speed: 100,
      transition: true,
      axis: null,
      reset: true,
      "reset-to-start": true,
      easing: "cubic-bezier(0, 0.55, 0.45, 1)",
      glare: true,
      "max-glare": 0.2,
      "glare-prerender": false,
      "mouse-event-element": null,
      gyroscope: true,
      gyroscopeMinAngleX: -15,
      gyroscopeMaxAngleX: 15,
      gyroscopeMinAngleY: -15,
      gyroscopeMaxAngleY: 15,
    }}
  >
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

<style scoped>
  .card:hover > figure > img {
    transform: scale(1.02);
  }
</style>
