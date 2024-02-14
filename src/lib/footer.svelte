<script>
  // @ts-nocheck
  import { Codepen, Github, Artstation } from "@icons-pack/svelte-simple-icons";
</script>

<main>
  <footer class="footer p-10 bg-base-200 text-neutral-content">
    <aside>
      <p></p>
    </aside>
    <nav>
      <h6 class="footer-title">Social</h6>
      <div class="grid grid-flow-col gap-4">
        <div class="icon"><Codepen /></div>
        <div class="icon"><Github /></div>
        <div class="icon"><Artstation /></div>
      </div>
    </nav>
  </footer>
</main>

<style>
  .icon {
    transition: all 0.15s ease-in;
    cursor: pointer;
  }
  .icon:hover {
    color: oklch(var(--in));
    transform: scale(130%);
  }
</style>
