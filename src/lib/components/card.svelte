<script>
  /** @type {{header:Snippet,content:Snippet,footer:Snippet}}*/
  let { header, content, footer } = $props();
</script>

<div class="card">
  <div class="hreader">
    {@render header()}
  </div>
  <div class="content">
    {@render content()}
  </div>
  <div class="footer">
    {@render footer()}
  </div>
</div>
