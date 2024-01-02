---
title: Blog!
---

{{ range .Site.data.recipes }}
<article>
  <h1>{{ .title }}</h1>
  <time>{{ .prep_time }}</time>
  <p>{{ .ingredients }}</p>
  <!-- Add more fields as needed -->
</article>
{{ end }}
