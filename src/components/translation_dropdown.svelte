<script>
  import { t, locale, locales } from "../lib/i18n";
</script>

<select
  class="select select-sm select-ghost w-full max-w-xs"
  aria-label="Change language"
  bind:value={$locale}
>
  {#each locales as l}
    <option value={l}>{l}</option>
  {/each}
</select>

<style>
  select:hover {
    scale: 1.05;
  }

  select:focus {
    scale: 1.05;
  }
</style>
