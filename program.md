---
title: Program
---

## Schedule


<table class="table table-striped table-hover text-center">
  <thead class="table-dark">
    <tr>
      <th scope="col"><b>Time</b></th>
      <th scope="col"><b>Event</b></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>9:00 - 10:00</td>
      <td>Opening Remarks and Keynote: Dr. Mor Vered</td>
    </tr>
    <tr>
      <td>10:00 - 10:30</td>
      <td>Author Lightning Talks</td>
    </tr>
    <tr>
      <td>10:30 - 11:00</td>
      <td>Coffee Break</td>
    </tr>
    <tr>
      <td>11:00 - 11:45</td>
      <td>Poster Session</td>
    </tr>
    <tr>
      <td>11:45 - 12:30</td>
      <td>Discussion Panel: <i>Perspectives on the Explainability Pipeline</i></td>
    </tr>
    <tr>
      <td>12:30 - 13:30</td>
      <td>Lunch</td>
    </tr>
    <tr>
      <td>13:30 - 14:00</td>
      <td>Intro for Writing Session, Plenary Brainstorming Topics</td>
    </tr>
    <tr>
      <td>14:00 - 15:00</td>
      <td>Writing Session in Breakout Groups</td>
    </tr>
    <tr>
      <td>15:00 - 15:30</td>
      <td>Coffee Break</td>
    </tr>
    <tr>
      <td>15:30 - 16:00</td>
      <td>Plenary Discussion (summary, next steps)</td>
    </tr>
    <tr>
      <td>16:00 - 16:10</td>
      <td>Closing Remarks</td>
    </tr>
  </tbody>
</table>


---------
## Speakers

### Keynote
<div class="container">
  <div class="row">
    {% for person in site.data.speakers.speakers %}
    <div class="col-12 mb-4">
      <div class="d-flex flex-row align-items-start" style="flex-wrap: wrap; gap: 1.5rem;">

        <div style="width: 200px; flex-shrink: 0;">
          <a href="{{ person.url }}" target="_blank" style="text-decoration: none;">
            <div class="card text-center">
              <img src="{{ person.image | relative_url }}" class="card-img-top" alt="{{ person.name }}">
              <div class="card-body">
                <h5 class="card-title">{{ person.name }}</h5>
                <p class="card-text">{{ person.affiliation }}</p>
              </div>
            </div>
          </a>
        </div>

        <div style="flex: 1; min-width: 250px;">
          <p style="font-size: 0.9rem; margin-bottom: 1rem;">{{ person.bio }}</p>
          <h5 style="font-size: 1rem; font-weight: 600; margin-bottom: 0.4rem;">{{ person.title }}</h5>
          <p style="font-size: 0.9rem;">{{ person.abstract }}</p>
        </div>

      </div>
    </div>
    {% endfor %}
  </div>
</div>

### Panelists

<!-- {% for person in site.data.speakers.panelists %}
- **{{ person.name }}**: {{ person.title }} at {{ person.affiliation }}
{% endfor %} -->

<!-- - **Oana Inel**: Postdoctoral Researcher at the University of Zurich
- **Debasis Ganguly**: Lecturer at the University of Glasgow
- **Gineke Wiggers**: Senior Technology Product Manager at Wolters Kluwer
- **Avishek Anand**: Associate Professor at TU Delft
- **Catherine Chen**: PhD Candidate at Brown University -->
