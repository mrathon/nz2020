---
title: "Organizers"
bg: wednesday
color: white
fa-icon: user
iconclr: wednesday
titleclr: wednesday
---

<div class="team">
<div class="row">

{% for person in site.data.committee.people %}
<div class="col-md-4">
<center>
<div class="team-player">
    <img src="img/organization/{{ person.image }}" alt="Thumbnail Image" class="img-raised img-circle" style="width:194px;height:194px;">
    <h4 class="title" style="color: #ffffff;">{{ person.name }}<br>
        <small class="text-muted" style="color: #337ab7;">{{ person.title }}</small>
    </h4>
    <p class="description" style="color: #ffffff;"> {{ person.affiliation }}</p>
    <a href="{{ person.twitter }}" class="btn btn-simple btn-just-icon"><i class="fa fa-twitter"></i></a>
</div>
</center>
</div>
  {% endfor %}
  </div>
</div>
