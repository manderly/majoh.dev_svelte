<script>
  export let position;
  export let companyName;
  export let startDate;
  export let endDate;
  export let accomplishments;
</script>

<div>
  <h1>{position} @ {companyName}</h1>
  <i>{startDate} - {endDate}</i>
  <ul>
    {#each accomplishments as accomplishment}
      <li>{accomplishment}</li>
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