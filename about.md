---
layout: page
title: Über uns
background: '/img/bg-contact.jpg'
---


Wir arbeiten seit über fünf Jahren daran, die Kontrollen von elektrischen Installationen für alle Beteiligten so einfach und unkompliziert wie möglich zu machen.

Persönlicher Kundenkontakt und eine gute Zusammenarbeit mit den Elektrizitätswerken und den Elektrikern und einen klaren und einfachen Ablauf sind uns wichtig und eine gute Vorraussetzungen für eine reibungslose Kontrolle.

So ist es möglich, unsere Kontrollen zielgerichtet, einfach und konstengünstig zu erledigen.

Ganz nach unserem Motto:
kompetent, einfach, persönlich.

<section id="team" class="bg-light-gray">
<div class="container">
           <div class="row">
               <div class="col-lg-12 text-center">
                   <h2 class="section-heading">Unser Team</h2>
            <!--       <h3 class="section-subheading text-muted">Lorem ipsum dolor sit amet consectetur.</h3> -->
               </div>
           </div>
           <div class="row">
               {% for member in site.people %}
               <div class="col-sm-4">
                   <div class="team-member">
                       <img src="img/team/{{ member.pic }}.jpg" class="img-responsive img-circle" alt="">
                       <h4>{{ member.name }}</h4>
                       <p class="text-muted">{{ member.position }}</p>
                       <ul class="list-inline social-buttons">
                           {% for network in member.social %}
                           <li>
                               <a href="{{ network.url }}">
                                   <i class="fa fa-{{ network.title }}"></i>
                               </a>
                           </li>
                           {% endfor %}

                       </ul>
                   </div>
               </div>
               {% endfor %}
           </div>
           <div class="row">
               <div class="col-lg-8 col-lg-offset-2 text-center">
                <!--   <p class="large text-muted">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aut eaque, laboriosam veritatis, quos non quis ad perspiciatis, totam corporis ea, alias ut unde.</p> -->
               </div>
           </div>
       </div>
</section>
