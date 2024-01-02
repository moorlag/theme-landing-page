---
title: Terms of Service
date: 2023-12-01
share: false
---

{{ range .site.data.recipes }}
<div>
  <h2>{{ .title }}</h2>
  <p>Preparation time: {{ .prep_time }}</p>
  <!-- Add more fields as needed -->
</div>
{{ end }}
