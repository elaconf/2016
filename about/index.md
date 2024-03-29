---
layout: page
title: About
order: 1
description: Ela Conf is a conference with a goal to create a safe, supportive, inspiring and comfortable _community_ for adult women (18+) to gain the confidence needed to become leaders, speakers, and teachers in the world of tech.
---

Ela Conf is a conference with a goal to create a safe, supportive, inspiring and comfortable _community_ for adult women (18+) to gain the confidence needed to become leaders, speakers, and teachers in the world of tech.

In an industry where women are so often marginalized, leadership skills are crucial to making an impact in the field and creating diversity in the workplace. Companies with greater top-level gender diversity perform better financially, are more empathetic, and more innovative. When women become leaders, the entire tech community benefits.

Ela Conf was held on the evening of Friday, November 4 and all day Saturday, November 5 at [The University of the Arts](/venue/) in Philadelphia.

Stay tuned for details on Ela Conf 2017 :sparkles:.

## Code of Conduct

Our [code of conduct](/code-of-conduct/) is the heart of our event. Please [reach out to us](mailto:hello@elaconf.com) if you have any concerns or there is something you would like to see included that isn’t.

## Organizers

<div class="speakers">
  {% assign organizers = site.organizers | sort: 'order' %}
  {% for organizer in organizers %}{% if organizer.image %}
  <a href="{{site.baseurl}}{{organizer.url}}" class="speaker">
    <div class="speaker-img" style="background-image:url(/2016/images/organizers/{{organizer.image}}), {{site.gradient}}">
    </div>
    <div class="speaker-name">{{organizer.title}}</div>
  </a>
  {% endif %}{% endfor %}
</div>
