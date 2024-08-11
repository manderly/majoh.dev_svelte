<script>
  export let titles;
</script>

<div>
  <ul>
    {#each titles as title}
      <li>{title}</li>
    {/each}
  </ul>
</div>