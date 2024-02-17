<script>
  // @ts-nocheck
  import { Github } from "@icons-pack/svelte-simple-icons";
  import ThemeConroller from "./theme_conroller.svelte";
  import TranslationDropdown from "./translation_dropdown.svelte";
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
      <!-- <TranslationDropdown /> -->
    </div>
    <div>
      <ThemeConroller />
    </div>
  </div>
</main>

<style>
</style>
