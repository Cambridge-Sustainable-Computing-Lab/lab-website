---
title: About
nav:
  order: 6
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-solid fa-circle-info" %}About us: contact, funding and info about Cambridge

We are part of the Cardiovascular Epidemiology Unit (CEU) in the Department of Public Health and Primary Care at the University of Cambridge (UK) and are based at the Heart and Lungs Research Institute (HLRI) on the biomedical campus.

<!-- ## {% include icon.html icon="fa-regular fa-envelope" %}Contact -->

{%
  include button.html
  type="email"
  text="Email Loïc"
  link="ll582@medschl.cam.ac.uk"
%}

{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/hBeL1PNsVATCC4997"
%}

{% include section.html %}

## Some snapshots

{% include figure.html image="images/cambridge/hlri_papworth.jpg" caption="View of HLRI and Papworth Hospital" width="100%" %}

{% capture content %}
  {% include figure.html image="images/cambridge/HLRI.jpg" caption="HLRI building" width="100%" %}
  {% include figure.html image="images/cambridge/cambridge_kings.jpg" caption="A classic view of Cambridge" width="100%" %}
  {% include figure.html image="images/cambridge/cambridge_punting.jpg" caption="River Cam" width="100%" %}
{% endcapture %}

{% include grid.html content=content %}

{%
  include figure.html
  image="images/team/CEU_away_day_2025.jpeg"
  caption="The 2025 CEU away day in Cambridge"
  width="100%"
%}

{% include section.html %}

## Funding and support

{% capture col1 %}
  [![Wellcome](/images/funders/wellcome-logo.png)](https://wellcome.org)
{% endcapture %}

{% capture col2 %}
  [![University of Cambridge](/images/funders/cambridge-logo.png)](https://www.cam.ac.uk)
{% endcapture %}

{%
  include cols.html
  col1=col1
  col2=col2
%}

{% capture col3 %}
  [![Cambridge NIHR BRC](/images/funders/cambridge-nihr-brc-logo.png)](https://cambridgebrc.nihr.ac.uk)
{% endcapture %}

{% capture col4 %}
  [![BHF](/images/funders/bhf-logo.png)](https://www.bhf.org.uk)
{% endcapture %}

{% capture col5 %}
  [![Software Sustainability Institute](/images/funders/ssi-logo.png)](https://www.software.ac.uk/)
{% endcapture %}

{%
  include cols.html
  col1=col3
  col2=col4
  col3=col5
%}

{% include section.html %}

## About Cambridge

{% capture text %}

A good (independent) guide about relocating to Cambridge is [available on MoverDB](https://moverdb.com/moving-to-cambridge-uk/). The University also has a lot of resources for this.

Cambridge is located around 55 miles north of London and has a population of ~180,000 people. Within Cambridge, most traffic is done by bike: the city is very flat and has the highest level of cycle use in the UK ([apparently](https://web.archive.org/web/20090605201526/http://www.statistics.gov.uk/CCI/SearchRes.asp?term=KS15&btnSubmit=Search)).

Transports: there are direct trains to London King's Cross (50min) and Stansted Airport is also nearby (30 miles and quick direct trains). __A new station, Cambridge South, is also expected to open ~100m from our office sometime in 2025!__

{%
  include button.html
  link="https://www.cam.ac.uk/about-the-university?ucam-ref=home-menu"
  text="Check out the University's website for more info"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/cambridge/map_UK-Cambridge.png"
  text=text
%}

<details markdown="1">
<summary>University Accommodation Service</summary>

The University Accommodation Service helps staff, students and visiting scholars who are affiliated to the University in their search for suitable accommodation in Cambridge. The dedicated accommodation team can provide access to a wide range of University-owned furnished and unfurnished properties, and has a database of private sector accommodation available for short and long-term lets. For further information and to register with this free service please visit [accommodation.cam.ac.uk](https://www.accommodation.cam.ac.uk/).

</details>

The BRC is at the centre of an immense amount of industry and academic activity. Ten minutes north is the Cambridge Station tech precinct which houses leading data science and AI companies, such as Microsoft Research, Amazon, Apple and Samsung AI. A short bus/cab ride south is the Wellcome Genome Campus, home to the Wellcome Sanger Institute, EMBL European Bioinformatics Institute, Genomics England and others. A 45 minute train south is the London King's Cross tech precinct, which includes the Alan Turing Institute, Google's London Headquarters, DeepMind and the Francis Crick Institute.

From [Wikipedia](https://en.wikipedia.org/wiki/Cambridge):
> Cambridge is at the heart of the high-technology Silicon Fen or Cambridge Cluster, which contains industries such as software and bioscience and many start-up companies born out of the university. Over 40 per cent of the workforce have a higher education qualification, more than twice the national average. The Cambridge Biomedical Campus, one of the largest biomedical research clusters in the world, includes the headquarters of AstraZeneca and the relocated Royal Papworth Hospital.

> The city, like most of the UK, has a maritime climate highly influenced by the Gulf Stream. Located in the driest region of Britain, Cambridge's rainfall averages around 570 mm (22.44 in) per year, around half the national average. Owing to its low-lying, inland, and easterly position within the British Isles, summer temperatures tend to be somewhat higher than areas further west, and often rival or even exceed those recorded in the London area. Typically the temperature will reach 25.1 °C (77.2 °F) or higher on over 25 days of the year over the 1981–2010 period.

{% include figure.html image="images/cambridge/Cambridge_Biomedical_Campus_map_Feb24.png" caption="Map of Cambridge Biomedical Campus."%}

{% include figure.html image="images/cambridge/biomedical-campus.jpg" caption="And an old aerial view of the Campus (outdated, a lot of the yellow circles are now built!)."%}
