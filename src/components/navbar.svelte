<script>
  // @ts-nocheck
  import { SiGithub } from "@icons-pack/svelte-simple-icons";
  import ThemeConroller from "./theme_conroller.svelte";
  import TranslationDropdown from "./translation_dropdown.svelte";
</script>

<main>
  <div class="navbar bg-base-100 dots">
    <div class="flex-none">
      <a
        href="https://github.com/ThunderCatXp"
        class="btn btn-square btn-ghost"
        aria-label="Github Profile"
      >
        <div>
          <SiGithub title="Github Profile" class="bg-primary-content" />
        </div>
      </a>
    </div>
    <div class="flex-1">
      <a href="https://github.com/ThunderCatXp" class="btn btn-ghost text-xl"
        >ThunderCat</a
      >
    </div>
    <div>
      <TranslationDropdown />
    </div>
    <div>
      <ThemeConroller />
    </div>
  </div>
</main>

<style>
  @keyframes spin {
    from {
      transform: rotate(0deg);
    }
    to {
      transform: rotate(360deg);
    }
  }

  a:hover > div {
    animation: spin 2s cubic-bezier(0.6, -0.28, 0.735, 0.045) infinite;
  }
</style>
