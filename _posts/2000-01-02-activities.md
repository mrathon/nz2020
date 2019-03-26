---
title: "About"
bg: clrnew
color: about
fa-icon: info-circle
iconclr: '#428bca'
titleclr: '#428bca'
---

# A hackathon for MRI professionals

<p style ="text-align: center; font-weight: bold; font-size:24px;"> To promote reproducibility, collaboration, and standards through open source practices in magnetic resonance. </p>

<br><br>

<p style ="text-align: center; font-style: italic; font-size:18px;"><a href="https://www.gnu.org/philosophy/hackathons.en.html" target="blank">"Hackathons are an accepted method of giving community support to digital development projects. The community invites developers to join an event which offers an encouraging atmosphere, some useful resources, and the opportunity to work on useful projects." - Richard M. Stallman</a></p> 

<center><p style ="text-align: center; font-style: bold; font-size:18px;">If you’ve never been to a hackathon, <a href="https://www.ohbmbrainmappingblog.com/blog/ohbm-hackathon-2017-a-first-timers-perspective">read this first timer’s perspective.</a></p></center>

<div class="row partners">
{% for item in site.data.projects.projects %}
  <div class="col s12 partner valign">
    <h4 style="color: #486a89; text-align: left"> {{ item.title }}  </h4>
    <a href="{{ item.url }}" target="blank"><img src="img/projects/{{ item.image }}"/></a>
    
  </div>
  {% endfor %}
  </div>

<br><br>

<p style ="text-align: center; font-weight: bold; font-size:24px;"> Registration opens on April 01, 2019. </p>
<center><a class="waves-effect waves-light btn red" href="https://agahkarakuzu.typeform.com/to/T8vk4k" target="blank">REGISTER</a></center>

<div class="row features">
  <div class="col s12 m4 feature">
    <i class="fa fa-comments-o fa-4x">
    </i>
    <h4> Socialize </h4>
    <p class="feature-description"> This is a great opportunity to enhance your network. Just get into the spirit of it! </p>
  </div>
  <div class="col s12 m4 feature">
    <i class="fa fa-laptop fa-4x">
    </i>
    <h4> Choose a project </h4>
    <p class="feature-description"> Bring your own, come up with one or join a project. The hackathon is made for everyone, from novice to pro.</p>****
  </div>
  <div class="col s12 m4 feature">
    <i class="fa fa-terminal fa-4x">
    </i>
    <h4> Hack </h4>
    <p class="feature-description"> Code to solve, teach to help and come together to create. All hands on deck!</p>
  </div>
</div>

