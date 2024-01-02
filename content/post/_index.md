---
title: Blog
---
{{ range .Site.Data.recipes }}
<article>
  <h1>{{ .title }}</h1>
  <time>{{ .date }}</time>
  <p>{{ .description }}</p>
  <!-- Add more fields as needed -->
</article>
{{ end }}
