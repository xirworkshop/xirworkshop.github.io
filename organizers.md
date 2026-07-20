---
title: Organizers
---

<div class="org-grid-wrap">
  {% for person in site.data.organizers.organizers %}
  <div class="org-grid-item">
    <a href="{{ person.url }}" target="_blank">
      <img src="{{ person.image | relative_url }}" alt="{{ person.name }}" class="org-circle-photo">
      <p class="org-grid-name">{{ person.name }}</p>
      <p class="org-grid-affil">{{ person.affiliation }}</p>
    </a>
  </div>
  {% endfor %}
</div>
