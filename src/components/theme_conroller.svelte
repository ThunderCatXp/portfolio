<script>
  import "boxicons";
</script>

<main>
  <label class="swap swap-rotate btn btn-square btn-ghost">
    <!-- this hidden checkbox controls the state -->
    <input type="checkbox" class="theme-controller" value="cupcake" aria-label="Toggle theme"/>

    <!-- sun icon -->
    <box-icon
      class="swap-off fill-current w-5 h-5"
      name="sun"
      type="solid"
      color="#A9ACBA"
    ></box-icon>

    <!-- moon icon -->
    <box-icon
      class="swap-on fill-current w-5 h-5"
      name="moon"
      type="solid"
      color="#232836"
    ></box-icon>
  </label>
</main>

<style>
</style>
