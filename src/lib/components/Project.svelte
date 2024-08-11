<script>
  export let projectName;
  export let src;
  export let githubLink;
  export let description;
  export let callToAction;
  export let liveLink;
</script>

  <div class="project">
    <div>
      <img class="project-preview" {src} alt={projectName}>
    </div>
    <div class="project-description">
      <h3>{projectName}</h3>
      <a href={githubLink}>Project GitHub</a>
      <p>{description}</p>
      <b>{callToAction}</b> <a href={liveLink}>{liveLink}</a>
    </div>
  </div>

<style>
  .project {
    display: grid;
    padding: 16px;
    grid-template-columns: 1fr 3fr;
    gap:2px;
  }
  .project-preview {
    width: 300px;
    padding:10px;
    border:1px solid #eee;
  }

  .project-description {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    margin-left:10px;
  }

  h3 {
    margin:0
  }

  table tr {
    vertical-align: top;
  }

  @media (max-width: 860px) {
    .project-preview {
      width: 100%;
      align-content:center;
    }
    .project {
      grid-template-columns: 1fr;
    }
}

</style>