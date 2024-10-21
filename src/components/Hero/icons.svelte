<script>
  // @ts-nocheck
  import {
    Javascript,
    Html5,
    CssThree,
    Svelte,
    Gnubash,
    Linux,
    Python,
    Figma,
    Adobeillustrator,
    Adobephotoshop,
    Awesomelists,
    Blender,
    Docker,
    Cisco,
    Vuedotjs,
    Github,
    Git,
  } from "@icons-pack/svelte-simple-icons";
</script>

<main>
  <div class="w-96">
    <div class="flex flex-row flex-wrap gap-1">
      <div class="icon"><Docker /></div>
      <div class="icon"><Javascript /></div>
      <div class="icon"><Html5 /></div>
      <div class="icon"><CssThree /></div>
      <div class="icon"><Svelte /></div>
      <div class="icon"><Vuedotjs /></div>
      <div class="icon"><Linux /></div>
      <div class="icon"><Cisco /></div>
      <div class="icon"><Python /></div>
      <div class="icon"><Github /></div>
      <div class="icon"><Gnubash /></div>
      <div class="icon"><Git /></div>
      <div class="icon"><Figma /></div>
      <div class="icon"><Adobeillustrator /></div>
      <div class="icon"><Adobephotoshop /></div>
      <div class="icon"><Awesomelists /></div>
      <div class="icon"><Blender /></div>
    </div>
  </div>
</main>

<style>
  .icon {
    transition: all 0.15s ease-in;
    cursor: pointer;
  }
  .icon:nth-child(even):hover {
    color: oklch(var(--p));
    transform: scale(130%);
  }

  .icon:nth-child(odd):hover {
    color: oklch(var(--a));
    transform: scale(130%);
  }
</style>
