<script>
  import "/node_modules/flag-icons/css/flag-icons.min.css";
  import { t, locale, locales } from "./i18n";
</script>

<select class="select w-full max-w-xs" bind:value={$locale}>
  {#each locales as l}
    <option value={l}>{l}</option>
  {/each}
</select>
