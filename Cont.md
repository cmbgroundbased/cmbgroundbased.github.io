---
layout: single
title:
author_profile: true
staff_members: true
---

Here the profile schedule of the person involved in the CMB-GB organization activities

<ul>
  {% for author in site.authors %}
    <li>
      <h2>{{ author.name }}</h2>
      <h3>{{ author.position }}</h3>
      <p>{{ author.content | markdownify }}</p>
    </li>
  {% endfor %}
</ul>


<ul>
    {% for author in site.data.authors %}
    <li>
        {{ author.display_name }}
        {{ author.avatar}}
    </li>
    {% endfor %}
</ul>
