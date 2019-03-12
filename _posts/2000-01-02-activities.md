---
title: "About"
bg: about
color: white
fa-icon: info-circle
---

#### Bringing together the ISMRM leaders in the field of reproducibility and open science.

# A hackathon for MRI professionals 

<center><a class="waves-effect waves-light btn bg-{{ page.border-color }}" href="https://agahkarakuzu.typeform.com/to/T8vk4k" target="blank">REGISTER</a></center>

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

<ul class="challenge collapsible" data-collapsible="accordion">
  <li>
    <div class="challenge-title collapsible-header"><i class="fa fa-terminal fa-5x"></i><b>Click. You should take a look at this function!</b></div>
    <div class="challenge-body collapsible-body">
     
<div class="row">

<div class="col s12 feature2">
{%highlight python%}
import ProjectLeader as prl
import Faculty  as fcl
import Organizer as org
import Trainee as trn 

def MRathon(you):

{%endhighlight%}
</div>
  
<div class="col s6 feature2">
  <ul>
  {%highlight haskell%}

  participants = [

  1  prl.Nikola_Stikov,

  2  prl.Lukas_Winter,

  3  prl.Daniel_Ennis,

  4  prl.Adrienne_Campbell-Washburn,

  5  prl.Joshua_Trzasko,

  6  prl.Simone_Angela Winkler,

  7  prl.Joao_Periquito,

  8  prl.Ruben_Pellicer,

  9  trn.Katy Keenan,

  10 org.Agah Karakuzu,

  11 org.Tommy Boshkovski,

  12 org.Mathieu Boudreau,

  13 Tobias Leutritz,

  14 Tom O'Reilly,

  15 Johnes Obungoloch,

  16 Erika Rave,

  17 Thomas Eigentler,

  {%endhighlight%}
  </ul>

  </div>
  <div class="col s6 feature2">
 {%highlight haskell%}
  18 Jelle Veraart,

  19 Alonso Ramirez,

  20 Bonny Biswas,

  21 Eric Borisch,

  22 Kevin Glaser,

  23 Nolan Meyer,

  24 Tim Kline,

  25 Jeff Fessler,

  26 Martin Uecker,

  27 Florian Knoll,

  28 Miki Lustig,

  29 Stefan Skare,

  30 Krishna Nayak,

  31 Justin Haldar,

  32 Joseph Cheng,

  33 Wiktor Olszowy,

  34 Matthias Dieringer]
  {%endhighlight%}
  </div>

  <div class="col s12 feature2">
{%highlight python%}
      if not you in participants: 
        participants.append(you)

      participants.set_location("Montreal","Quebec","Cadana") # You will love it
      
      if location.get_temperature < -10: # But you may never know... 
        raise ValueError('Oh Canada!')

      participants.set_event_duration(2*24*60*60) 
      
      try:
        
        take_home = participants.get_project_done() 
      
      except:
       
        take_home = participants.start_new_project()
     
      finally:
        
        participants.learn_new_stuff()

        participants.socialize() 

        participants.party() 

        take_home = participants.have_great_time()  
      
      return take_home 

{%endhighlight%}
</div>
    
  </div>

    
     
    </div>
  </li>
</ul>
