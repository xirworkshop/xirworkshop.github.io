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
      <td>9:00 - 9:45</td>
      <td>Opening Remarks and Keynote: Oana Inel</td>
    </tr>
    <tr>
      <td>9:45 - 10:30</td>
      <td>Discussion Panel: <i>Evaluation of Explanations</i></td>
    </tr>
    <tr>
      <td>10:30 - 11:00</td>
      <td>Coffee Break</td>
    </tr>
    <tr>
      <td>11:00 - 11:45</td>
      <td>Author Lightning Talks</td>
    </tr>
    <tr>
      <td>11:45 - 12:30</td>
      <td>Round Table Discussions & Writing</td>
    </tr>
    <tr>
      <td>12:30 - 14:00</td>
      <td>Lunch</td>
    </tr>
    <tr>
      <td>13:00 - 14:30</td>
      <td>Poster Session</td>
    </tr>
    <tr>
      <td>14:30 - 15:15</td>
      <td>Discussion Panel: <i>Needs and Challenges of Stakeholders/Practitioners in XIR</i></td>
    </tr>
    <tr>
      <td>15:15 - 16:00</td>
      <td>Round Table Discussions & Writing</td>
    </tr>
    <tr>
      <td>16:00 - 16:30</td>
      <td>Closing / Coffee Break</td>
    </tr>
  </tbody>
</table>


---------
## Speakers

### Keynote
<div class="container">
{% include head.html %}
  <div class="row">
    {% for person in site.data.speakers.speakers %}
    <div class="col-12 mb-4">
      <div class="d-flex flex-row align-items-start" style="flex-wrap: wrap;">
        
        <div style="width: 200px; flex-shrink: 0; margin-right: 20px;">
          <a href="{{ person.url }}" target="_blank" style="text-decoration: none;">
            <div class="card text-center">
              <img src="{{ person.image }}" class="card-img-top" alt="{{ person.name }}" style="max-height: 200px; width: 150px; object-fit: contain; margin: auto; padding-top: 10px;">
              <div class="card-body">
                <h5 class="card-title" style="font-size: 1rem;">{{ person.name }}</h5>
                <p class="card-text" style="font-size: 0.9rem;">{{ person.affiliation }}</p>
              </div>
            </div>
          </a>
        </div>

        <div style="flex: 1;">
          <p class="card-text" style="font-size: 0.9rem;"> {{ person.bio }}</p>
        </div>

      </div>
      
      <!-- <div style="margin-top: 10px;">
        <h5 class="card-title" style="font-size: 1rem;">{{ person.name }}</h5>
        <p class="card-text" style="font-size: 0.9rem;">{{ person.affiliation }}</p>
      </div> -->

    </div>
    {% endfor %}
  </div>
</div>

### Panelists

<!-- {% for person in site.data.speakers.panelists %}
- **{{ person.name }}**: {{ person.title }} at {{ person.affiliation }}
{% endfor %} -->

- **Oana Inel**: Postdoctoral Researcher at the University of Zurich
- **Debasis Ganguly**: Lecturer at the University of Glasgow
- **Gineke Wiggers**: Senior Technology Product Manager at Wolters Kluwer
- **Avishek Anand**: Associate Professor at TU Delft
- **Catherine Chen**: PhD Candidate at Brown University
