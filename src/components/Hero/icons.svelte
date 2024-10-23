<script>
  // @ts-nocheck
  import {
    SiJavascript,
    SiHtml5,
    SiSvelte,
    SiGnubash,
    SiLinux,
    SiPython,
    SiFigma,
    SiAdobeillustrator,
    SiAdobephotoshop,
    SiAwesomelists,
    SiBlender,
    SiDocker,
    SiCisco,
    SiVuedotjs,
    SiGithub,
    SiGit,
    SiHono,
    SiCss3,
  } from "@icons-pack/svelte-simple-icons";
</script>

<main>
  <div class="w-96">
    <div class="flex flex-row flex-wrap gap-1">
      <div class="icon"><SiDocker /></div>
      <div class="icon"><SiJavascript /></div>
      <div class="icon"><SiCss3 /></div>
      <div class="icon"><SiHtml5 /></div>
      <div class="icon"><SiSvelte /></div>
      <div class="icon"><SiHono /></div>
      <div class="icon"><SiVuedotjs /></div>
      <div class="icon"><SiLinux /></div>
      <div class="icon"><SiCisco /></div>
      <div class="icon"><SiPython /></div>
      <div class="icon"><SiGithub /></div>
      <div class="icon"><SiGnubash /></div>
      <div class="icon"><SiGit /></div>
      <div class="icon"><SiFigma /></div>
      <div class="icon"><SiAdobeillustrator /></div>
      <div class="icon"><SiAdobephotoshop /></div>
      <div class="icon"><SiAwesomelists /></div>
      <div class="icon"><SiBlender /></div>
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
