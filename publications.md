---
layout: homepage
permalink: /publications/
---

{% if site.auto_dark_mode %}
<style>
  @import url("{{ '/assets/css/style.css' | relative_url }}");
  @import url("{{ '/assets/css/publications.css' | relative_url }}");
</style>
{% else %}
<style>
  @import url("{{ '/assets/css/style-no-dark-mode.css' | relative_url }}");
  @import url("{{ '/assets/css/publications-no-dark-mode.css' | relative_url }}");
</style>
{% endif %}

{% include publications.md %}
