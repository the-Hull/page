---
title: "Projects"
author_profile: false
excerpt: "Professional and personal experiences."
header:
  image: /assets/images/headers/cv.jpg
sidebar:
  nav: "res"
gallery-ecohydrology:
    - url: /assets/images/research/ForestFloor_ET_proportion.png
      image_path: /assets/images/research/ForestFloor_ET_proportion.png
      alt: "Partitioning of subcanopy evapotranspiration in six representative locations of a shallow wetland through summer."
    - url: /assets/images/research/wetland.png
      image_path: /assets/images/research/wetland.png
      alt: "Forested wetland post fire."  
    - url: /assets/images/research/ForestFloor_ET_control.png
      image_path: /assets/images/research/ForestFloor_ET_control.png
      alt: "Relationship between daily subcanopy water loss from a shallow wetland through summer."
gallery-madingley:
    - url: /assets/images/research/trophic-dynamics.png
      image_path: /assets/images/research/trophic-dynamics.png
      alt: "Trophic dynamics across 100 years (n = 100)"
    - url: /assets/images/research/trophic-dynamics_exp.png
      image_path: /assets/images/research/trophic-dynamics_exp.png
      alt: "Trophic dynamics between experiments."
permalink: /research/
---


## Research <a name = "research"></a>


### Ecohydrological functioning of shallow Boreal Plain (Canada) wetlands and implications for land reclamation in the Athabasca oil sands  (PhD)<a name = "PhD" ></a>

My research focuses on the interplay of hydrology and ecology of shallow, ephemeral wetlands in the Boreal Plain (Alberta, Canada). My work is elucidating processes that allow surplus water generation in a sub-humid environment, linking plant community dynamics and vegetation structure with water movement at multiple scales (i.e. leaf to catchment). With this research I hope to inform the reclamation of mine closure sites in the [Athabasca Oil Sands Region](https://en.wikipedia.org/wiki/Athabasca_oil_sands), where the reconstruction of ecosystems often requires estimating delicate water balances to meet future, often conflicting goals (e.g. preventing mass movement/slope failures vs. generating surface runoff vs. groundwater recharge).

This research is part of a highly collaborative and inter-disciplinary project led by multiple universities based in the UK (University of Birmingham) and Canada (Universities of [Alberta](https://devitogroup.squarespace.com/), [McMaster](http://ecohydrology.mcmaster.ca/) and [Waterloo](http://env-blogs.uwaterloo.ca/rpetrone/)), as well as multiple partners from industry and NGOs.

{% include gallery id="gallery-ecohydrology" caption="Atmospheric water losses via different pathways from representative locations in a shallow wetland (left), their meteorological control (right) and an exemplary Boreal Plain wetland impacted by fire (center)." %}



#### Main objectives

- Identify water redistributing mechanisms (e.g. via runoff, hydraulic redistribution, flow reversals) by establishing water balance for an exemplary, ephemeral wetland; given the sub-humid climate and low runoff ratios, atmospheric fluxes and changes in storage in relation to seasonal dynamics are the main focus.

- Assess impact of water redistribution on productivity of downstream and adjacent ecosystems; this is mainly achieved through proxies of plant water use (e.g. sap flow) and tree productivity and their variable expression throughout climate cycles.

- Develop concept of shallow (ephemeral) wetlands and highlight main processes that can be applied for land reclamation operations in the Athabasca Oil Sands to meet water balance demands across scales (i.e. for maintaining individual landscape units or generating runoff at larger scales for endpit lakes).




#### Recent outputs and publications


- <small> **Hurley, A.**, Kettridge, N., Devito, K., Hokanson, K. and Krause, S., 2017, April. A concept of ephemeral wetlands as water-transmitting landscape units in Canada's Western Boreal Plain. In *EGU General Assembly Conference Abstracts* (Vol. 19, p. 13113). </small>

- <small> **Hurley, A.,** Kettridge, N., Devito, K., Hokanson, K., Leonard, R., Krause, S. and Waddington, J.M., 2017, April. Spatio-temporal dynamics of evapotranspiration from forested, ephemeral wetlands and its implication for hydrologic connectivity in the Western Boreal Plain in Alberta, Canada. In *EGU General Assembly Conference Abstracts* (Vol. 19, p. 13592). </small>

- <small> Probert, S., Kettridge, N., Devito, K. and **Hurley, A.**, 2017, April. Ecohydrology of the wetland-forestland interface: hydrophobicity in leaf litter and its potential effect on surface evaporation. In *EGU General Assembly Conference Abstracts* (Vol. 19, p. 8445).
</small>



## Simulating impacts of carnivore functional diversity on ecosystem functioning on large spatial and temporal scales <a name = "BEF"></a>

Carnivore community composition and richness, i.e. which and how many functional groups are present, control trophic dynamics and thereby regulate ecosystem
functioning (ESF). Mechanisms underlying this regulation are mainly inferred via
small-scale (temporal, spatial) experiments with restricted species pools. This limits their application to real-world systems, as results are often specific to a given time (e.g. season), place (e.g. plot or ecoregion), while interactions are generally only observed across few or adjacent trophic levels.

The [*Madingley Model*](https://madingley.github.io/), termed a general ecosystem model, is an agent-based, spatially-explicit model developed by [Microsoft Research in Cambridge](https://www.microsoft.com/en-us/research/lab/microsoft-research-cambridge/) and the [UNEP-WCMC](https://www.unep-wcmc.org/). It is a pioneering effort in trying to overcome aforementioned limitations.

Using the *Madingley Model*, this study tested if (i) these diversity effects are still found when experiments are vastly extended in scale and complexity to more accurately mimic natural systems, and (ii) whether climate altered these effects.


{% include gallery id="gallery-madingley" caption="Exemplary trophic dynamics simulated with *Madingley*, showing development of biomass and abundance densities over time (left) and for varying degrees of carnivore diversity (right)." %}

<small> *This research was done in collaboration with Drs Mike Harfoot and Drew Purves, and supported financially by the European Commission through the program Erasmus Mundus Master Course - International Master in Applied Ecology" (EMMC-IMAE) (FPA 532524-1-FR-2012-ERA MUNDUS-EMMC)* </small>

#### Recent outputs and publications

<small> Watch this space - a manuscript is currently in preparation for publication. </small>

## Software development <a name = "software"> </a>

Research is generally highly domain and application specific and therefore often requires unique and tailored data analyses approaches. While specialized, many approaches are well established within scientific communities, yet are applied on a variety of platforms in a non-standardized manner. By developing and distributing well-documented, open-source software, such analyses can become more accessible, aiding in advancing science toward more reproducibility.

My software is written in [R (for statistical computing)](https://www.r-project.org/) and freely available via my [GitHub repositories](www.github.com/the-Hull).

### Current Projects

- <small> **RAPTOR** (Row And Tracheid Organizer in R): This packages performs wood cell anatomical data analyses on spatially explicit xylem (tracheids) datasets derived from wood anatomical thin sections. The package includes functions for the visualisation, alignment and detection of continuous tracheid radial file (defines as rows) and tracheid position within an annual ring of coniferous species. (Note: [Richard L. Peters](http://www.wsl.ch/info/mitarbeitende/peters/index_EN) is the project-lead and behind the fascinating mathematics; my duties are ensuring that the package met criteria for submission to software archives by adjusting code, efficiency and structure). </small>


## Data science products <a name = "data-science"></a>

Science is extremely fun (I hope you agree), yet only useful (beyond being stimulating) if results are communicated to audiences appropriately. One highly accessible way of achieving this are well-crafted, interactive data science products that allow exploring a given inference (e.g. mechanism or concept) with supporting data. I use a variety of tools based around [R (for statistical computing)](https://www.r-project.org/) and associated packages.

### Current Projects

- <small> *In development*. Online public outreach and data exploration platform for the [Birmingham Institute of Forest Research (BIFoR)](http://www.birmingham.ac.uk/research/activity/bifor/index.aspx). An early version is available [here](https://www.aglhurley.shinyapps.io/bifor).</small>
