<script>
  // @ts-nocheck
  import { Github } from "@icons-pack/svelte-simple-icons";
  import ThemeConroller from "./theme_conroller.svelte";
</script>

<main>
  <div class="navbar bg-base-100 dots">
    <div class="flex-none">
      <a
        href="https://github.com/ThunderCatXp"
        class="btn btn-square btn-ghost"
      >
        <Github title="Github Profile" class="bg-primary-content" />
      </a>
    </div>
    <div class="flex-1">
      <a href="https://github.com/ThunderCatXp" class="btn btn-ghost text-xl"
        >ThunderCat</a
      >
    </div>
    <div>
      <ThemeConroller />
    </div>
    <div>
      <!-- <TranslationDropdown /> -->
    </div>
  </div>
</main>

<style>
  .dots {
    background-image: radial-gradient(oklch(var(--n)) 5%, transparent 0%);
    background-size: 3px 3px;
  }
</style>
