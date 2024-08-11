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

<style>
  header {
    background-color: #f2f2f2;
    padding: 20px;
    text-align: center;
  }

  h1 {
    color: #333;
    font-size: 24px;
    margin: 0;
  }
</style>