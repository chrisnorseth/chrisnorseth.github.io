---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<style>
  .cv-content h1 {
    margin-top: 1.35em;
    margin-bottom: 0.35em;
  }

  .cv-content h1:first-of-type {
    margin-top: 0;
  }

  .cv-content h1 + h2 {
    margin-top: 0.6em;
  }

  .cv-content .cv-section-extra-space {
    height: 0.55em;
  }

  .cv-content .cv-section-bottom-space {
    height: 0.55em;
  }

  .cv-content .cv-service-list {
    margin-top: 0.2em;
  }

  .cv-content .cv-service-list > li {
    margin-bottom: 0.45em;
  }

  .cv-content .cv-service-list .list__item {
    margin-bottom: 0;
  }

  .cv-content .cv-service-list .archive__item-title {
    margin-top: 0;
    margin-bottom: 0.15em;
  }

  .cv-content .cv-service-list .archive__item-excerpt {
    margin-bottom: 0.25em;
  }

  .cv-content .cv-teaching-list .archive__item-title {
    margin-top: 0;
    margin-bottom: 0.15em;
  }

  .cv-content .cv-teaching-list .archive__item-excerpt {
    margin-bottom: 0.25em;
  }

  .cv-content .cv-research-role {
    font-size: 1.3em;
  }

  .cv-download {
    margin-bottom: 1.2em;
  }
</style>

<p class="cv-download">
  <a href="{{ base_path }}/files/Norseth_CV.pdf" class="btn" download>
    <i class="fa fa-download" aria-hidden="true"></i> Download CV
  </a>
</p>

<div class="cv-content" markdown="1">

Education
======
* Ph.D in Physics, University of Utah, 2028 (expected)
* M.S. in Physics, University of Utah, 2025
* B.S. in Physics, University of Utah, 2021


Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>


Research Experience
======
* <strong class="cv-research-role">Graduate Research Assistant</strong>  
  PI: Dr. Daniel Wik  
  *University of Utah*

  * **X-ray Cross-Calibration** (2025 - Present)
    * ***Thesis project***
    * **Processed 182 observations of 36 galaxy clusters (9.1 Ms of data)**
    * Spatially characterized 12 clusters in extreme detail
    * Studying the effect of instrumentation on galaxy cluster temperature measurements

  * **RX J1347** (2026 - Present)
    * ***Project lead***
    * Full spatial characterization of galaxy cluster emission
    * Investigating potential IC emission in a cluster merger

  * **Abell 754** (2026 - Present)
    * ***Drafted first author paper***
    * Spatially characterized in detail
    * Exploring shock strength and equilibration models in the cluster merger A754

  * **MACS J1752** (2026 - Present)
    * ***Project lead***
    * Will perform full spatial characterization of cluster emission
    * Investigating potential IC emission in a cluster merger
    * Followup to ZWCL 1856


  * **XRISM Cross Calibration w/ Abell 2029** (2024 - Present)
    * ***Collaborator***
    * Understanding cross-calibration between XRISM (XTend and Resolve) and NuSTAR
    * Processed and analyzed NuSTAR data


  * **PHEMTO Core Member** (2026)
    * ***Mission concept proposal***: The Polarimetric High Energy Modular Telescope Observatory
    * Simulated temperature profile across shock front in A665 and impact on equilibration models
    * Contributed to proposal, presented at X-Ray Universe


  * **Double Radio Relic Galaxy Cluster ZWCL+1856** (2024 - 2026) 
    * ***Published second author paper***
    * Remote/Visiting Collaboration with MIT Kavli Institute for Astrophysics and Space Research (PI: Dr. Aysegül Tümer) 
    * Investigated IC and B field strength in galaxy cluster merger
    * Visited MIT May 2024


  * **Equilibration in Galaxy Cluster Merger A665** (2023-2025)
    * ***Published first author paper***
    * Conducted detailed temperature analysis across shock front
    * Derived shock heating models for electron-ion equilibration

* <strong class="cv-research-role">Post-Bacc/Undergraduate Research Assistant</strong>  
  PI: Dr. Daniel Wik  
  *University of Utah*

  * **STAR-X Gas Clumping Simulations** (2021-2023)
    * ***Published first author paper***
    * Assessed sensitivity of STAR-X, a NASA MIDEX probe in phase A study
    * Constructed simulations and analysis pipelines
    * Simulated gas clumping in galaxy cluster outskirts


Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

<div class="cv-section-bottom-space"></div>

Successful Observing and Funding Proposals
======
* **PI**, 2026: *Graduate Student Travel Grant*, Department of Physics and Astronomy, University of Utah, $1250
* **PI**, 2026: *NuSTAR*, “3C 438: Constraining a Shock in one of the Hottest Clusters in the Universe,” 300 ks, C priority
* **Co-I**, 2026: *XRISM*, “Turbulence and Accurate Temperatures in Abell 2204,” 250 ks (PI: Daniel Wik) - C priority
* **Co-I**, 2026: *XRISM*, “CL 0217+70: The First XRISM Look at a Galaxy Cluster Merger Shock,” 310 ks (PI: Aysegül Tümer) - C priority
* **Co-I**, 2026: *NuSTAR*, “Shock Front and Inverse Compton Search Across the Double Radio Relics of MACS J1752.0+4440,” 200 ks (PI: Aysegül Tümer) - B priority
* **Co-I**, 2026: *NuSTAR*, “Triangulum Australis: Uncovering a Merger in an Obscure(d) Galaxy Cluster,” 125 ks (PI: Daniel Wik) - B priority
* **Co-I**, 2025: *NuSTAR*, “Hot Gas, Hydrostatic Mass, and Inverse Compton Constraints in Abell 1914 & Abell 1689,” 220 ks, C priority (PI: Daniel Wik)
* **Co-I**, 2024: *ADAP*, “X-ray Cross-calibration and the Impact on Cluster Cosmology,” $449,098 (PI: Daniel Wik)
* **Co-I**, 2024: *XRISM*, “Gas Dynamics in the Line-of-Sight Merger Abell 2163 with XRISM,” 200 ks, $176,173 (PI: Daniel Wik)

**Research Supported by:**
  * NASA NuSTAR GO Grant NNX17AH31G (PI: Daniel Wik)
  * NASA NuSTAR GO Grant NNH22ZDA001N (PI: Aysegül Tümer)


<div class="cv-section-bottom-space"></div>
  

Service and leadership
======
<ul class="cv-service-list">
{% assign service_items = site.service | sort: "order" %}
{% for post in service_items %}
  <li>{% include archive-single-service.html %}</li>
{% endfor %}
</ul>


Teaching
======
<ul class="cv-teaching-list">
{% for post in site.teaching reversed %}
  <li>{% include archive-single-teaching-cv.html %}</li>
{% endfor %}
</ul>

</div>
