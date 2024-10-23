<script>
  // @ts-nocheck
  import {
    SiCodepen,
    SiGithub,
    SiGmail,
  } from "@icons-pack/svelte-simple-icons";
</script>

<main>
  <footer class="footer p-10 bg-base-100 dots">
    <aside></aside>
    <nav>
      <h6 class="footer-title">Social</h6>
      <div class="grid grid-flow-col gap-4">
        <a
          class="icon"
          href="https://codepen.io/ThunderCatXp"
          aria-label="Codepen Profile"
        >
          <SiCodepen />
        </a>
        <a
          class="icon"
          href="https://github.com/ThunderCatXp"
          aria-label="Github Profile"
        >
          <SiGithub />
        </a>
        <a
          class="icon"
          href="mailto:thundercatxp@yahoo.com"
          aria-label="E-mail"
        >
          <SiGmail />
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
</style>
