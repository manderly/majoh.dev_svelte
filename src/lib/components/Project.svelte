<script>
  export let projectName;
  export let githubLink;
  export let description;
  export let liveLink;
</script>

<div>
  <h3>{projectName}</h3>
  <a href={githubLink}>Project GitHub</a>
  <p>{description}</p>
  See it live: <a href={liveLink}>{liveLink}</a>
</div>

<style>
</style>