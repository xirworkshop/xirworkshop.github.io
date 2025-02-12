---
title: Organizers
---

<div class="container">
{% include head.html %}
  <div class="row justify-content-center">
    {% for person in site.data.organizers.organizers %}
    <div class="col-md-4 col-sm-6 mb-4">
        <a href="{{ person.url }}" target="_blank">
            <div class="card text-center">
                <img src="{{ person.image }}" class="card-img-top" alt="{{ person.name }}">
                <div class="card-body">
                <h5 class="card-title">{{ person.name }}</h5>
                <p class="card-text">{{ person.affiliation }}</p>
                </div>
            </div>
        </a>
    </div>
    {% endfor %}
  </div>
</div>