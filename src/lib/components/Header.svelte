<script>
  export let title;
</script>

<header>
  <div class="links-container">
    <a class="site-navigation-link" href="https://github.com/manderly">Github</a>
    <a class="site-navigation-link" href="https://www.linkedin.com/in/majoh/">LinkedIn</a>
    <a class="site-navigation-link" href="https://tilcode.com/">Blog</a>
  </div>
  <h1>{title}</h1>
</header>

<style>
  .links-container {
    display: flex;
    justify-content: flex-end;
    gap: 30px;
    margin-top:10px;
    margin-bottom: 20px;
  }
</style>