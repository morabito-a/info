---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<p style="font-size: 1.5em; font-weight: bold;">Thesis:</p>

* Ph.D. in Engineering Sciences and Technology, Université libre de Bruxelles, Belgium.<br>
[Thesis: Experimental and numerical analysis of a Pump as Turbine in micro Pumped Hydro Energy Storage
](https://difusion.ulb.ac.be/vufind/Record/ULB-DIPOT:oai:dipot.ulb.ac.be:2013/326182/Holdings)
* M.Sc. in Science of Management, Vrije Universiteit Brussel, Belgium.<br> 
[Thesis: Business Model For Energy Management Enterprises](https://www.researchgate.net/publication/352216001_Business_Model_For_Energy_Management_Enterprises?channel=doi&linkId=60bf6773458515bfdb5014bf&showFulltext=true)
* M.Sc. in Energy Engineering - Power Generation, Politecnico di Milano, Italy.<br> 
[Thesis: Design method and optimization of Deriaz pump turbine for hydraulic energy storage](https://www.politesi.polimi.it/handle/10589/93737)

