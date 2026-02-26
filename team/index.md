---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team


  {% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}

  {% include list.html data="members" component="portrait" filter="group == 'current-members'" %}

  {% include list.html data="members" component="portrait" filter="role == 'mascot'" style="small" %}

## Honorary members & visitors

Visiting or based in other teams or institutes, they are key contributors to our different projects!

  {% include list.html data="members" component="portrait" filter="group == 'honorary-long-term'" %}

  {% include list.html data="members" component="portrait" filter="group == 'honorary' or group == 'visitor'" %}

{% include section.html highlight=true %}

<!--
#### The Lab is recruiting now!

We are looking for a diverse group of people to bring new and unique perspectives to the different projects of the group.

  {% include button.html icon="fa-solid fa-handshake-angle" text="Join the Team" link="join" style="button" %}
-->

 We are always happy to hear from talented researchers, more details on the [Join page](/join). 

{% include section.html %}

{%
  include figure.html
  image="images/team/2026_Christmas dinner.jpg"
  caption="The Lab's 2025 Christmas dinner'."
  width="100%"
%}

{% include section.html %}

## Alumni

Gone but not forgotten. These are past group members or affiliates who have moved on to new exciting roles but have all made lasting contributions to the science we do.

  {% include list.html data="members" component="portrait" filter="group == 'alumni'" style="small" %}


<!-- ## Affiliated members -->
