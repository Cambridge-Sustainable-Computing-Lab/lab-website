---
title: Projects
nav:
  order: 1
  tooltip: Research, tools, policy work, frameworks and more.
---

<!-- TODO create dedicated page discussing "funders" projects -->

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

Our projects are a combination of open-source tools, sustainability research projects, and policy work, all aiming to enable and promote sustainable computing.

    {% comment %}
    
    {% include tags.html tags="publication, resource, website" %}
    
    {% include search-info.html %}
    
    {% endcomment %}

{% include list.html component="card" data="projects" filter="group == 'current'" %}


    {% comment %}
    
    {% include section.html %}
    
    ## Previous
    
    Before starting his lab, Loïc worked on several projects
    
    {% include list.html component="card" data="projects" filter="group == 'concluded'" style="small" %}
    
    {% endcomment %}
