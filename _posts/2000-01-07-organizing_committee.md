---
title: "Projects"
bg: about
color: white
fa-icon: info-circle
---

<div class="team">
{% for person in site.data.committee.people %}
<div class="team-player">
    <img src="img/{{ person.img }}" alt="Thumbnail Image" class="img-raised img-circle" style="width:170px;height:194px;">
    <h4 class="title" style="color: #ffffff;">{{ person.name }}<br>
        <small class="text-muted" style="color: #337ab7;">{{ person.title }}</small>
    </h4>
    <p class="description" style="color: #ffffff;"> {{ person.affiliation }}</p>
    <a href="{{ person.twitter }}" class="btn btn-simple btn-just-icon"><i class="fa fa-twitter"></i></a>
</div>
  {% endfor %}
  </div>
