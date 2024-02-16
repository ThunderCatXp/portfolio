<script>
  // @ts-nocheck
  import { Codepen, Github, Artstation } from "@icons-pack/svelte-simple-icons";
</script>

<main>
  <footer class="footer p-10 bg-base-100 dots">
    <aside></aside>
    <nav>
      <h6 class="footer-title">Social</h6>
      <div class="grid grid-flow-col gap-4">
        <a class="icon" href="https://codepen.io/ThunderCatXp">
          <Codepen />
        </a>
        <a class="icon" href="https://github.com/ThunderCatXp">
          <Github />
        </a>
        <a class="icon" href="https://www.artstation.com/thundercat_art">
          <Artstation />
        </a>
      </div>
    </nav>
  </footer>
</main>

<style>
  a {
    transition: all 0.15s ease-in;
    cursor: pointer;
  }
  a:hover {
    color: oklch(var(--in));
    transform: scale(150%);
  }
  a:hover:visited {
    color: oklch(var(--s));
  }
</style>
