<script>
  export let position;
  export let location;
  export let companyName;
  export let startDate;
  export let endDate;
  export let accomplishments;
</script>

<div class="position-container">
  <div class="position-title"><h3>{position} @ {companyName}</h3> <i class="start-and-end-date">{startDate} - {endDate}</i></div>
  <span>{location}</span>
  <ul>
    {#each accomplishments as accomplishment}
      <li>{accomplishment}</li>
    {/each}
  </ul>
</div>

<style>
  .position-container {
    margin-bottom: 30px;
  }

  .position-title {
    display: flex;
    justify-content: space-between;
    align-items:end;
    margin-top:0;
    margin-bottom:3px;
  }

</style>