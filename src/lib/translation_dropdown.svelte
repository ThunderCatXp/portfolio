<script>
  import "/node_modules/flag-icons/css/flag-icons.min.css";
  let curr = "us";
</script>

<details class="dropdown">
  <summary class="m-1 btn btn-square btn-ghost"
    ><span class="fi fi-{curr}"></span></summary
  >
  <ul class="p-2 shadow menu dropdown-content z-[1] bg-base-100 rounded-box">
    <li>
      <button
        on:click={() => {
          curr = "ru";
        }}
        class="fi fi-ru"
      ></button>
    </li>

    <li>
      <button
        on:click={() => {
          curr = "pl";
        }}
        class="fi fi-pl"
      ></button>
    </li>

    <li>
      <button
        on:click={() => {
          curr = "us";
        }}
        class="fi fi-us"
      ></button>
    </li>
  </ul>
</details>
