<script>
  import { t, locale, locales } from "./i18n";
</script>

<select class="select select-sm w-full max-w-xs" bind:value={$locale}>
  {#each locales as l}
    <option value={l}>{l}</option>
  {/each}
</select>
