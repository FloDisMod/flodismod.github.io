---
title: 
feature_text: |
  Ongoing Research

feature_image: "/assets/cover_photo/pier.png"
feature_credit: Photo by Dr. Tamer Oraby
permalink: /ongoing-research/
strip_title: true

---

*The information presented on this page is confidential and is made available solely for the use of reviewers and collaborators. Please do not share or distribute without permission.*

---

<style>
.onpage-layout {
  display: flex;
  gap: 2rem;
  align-items: flex-start;
}

.onpage-nav {
  position: sticky;
  top: 100px;
  flex: 0 0 auto;
  white-space: nowrap;
  background: #f5f5f5;
  border-left: 3px solid #bf5700;
  padding: 0.75rem 1rem;
  border-radius: 4px;
  font-family: Helvetica, sans-serif;
}

.onpage-nav strong {
  display: block;
  margin-bottom: 0.5rem;
  color: #333;
  font-size: 13px;
}

.onpage-nav ul {
  list-style: none;
  margin: 0;
  padding: 0;
}

.onpage-nav ul li {
  margin-bottom: 0.4rem;
}

.onpage-nav ul li a,
.onpage-nav ul li a:link,
.onpage-nav ul li a:visited,
.onpage-nav ul li a:hover,
.onpage-nav ul li a:focus,
.onpage-nav ul li a:active {
  color: #000;
  text-decoration: none !important;
  background-image: none !important;
  background: none !important;
  box-shadow: none !important;
  border-bottom: none !important;
  text-shadow: none !important;
  outline: none;
  font-size: 14px;
  font-weight: normal;
  line-height: 1.4;
  display: block;
  padding: 3px 0;
}

.onpage-nav ul li a.active,
.onpage-nav ul li a.active:link,
.onpage-nav ul li a.active:visited {
  color: #bf5700 !important;
  font-weight: bold !important;
  text-decoration: underline !important;
  text-underline-offset: 3px;
}

.onpage-content {
  flex: 1;
  min-width: 0;
}
</style>

<div class="onpage-layout">

<div class="onpage-nav">
  <strong>On this page</strong>
  <ul>
    <li><a href="#west-nile-virus">West Nile Virus</a></li>
    <li><a href="#chagas-disease">Chagas Disease</a></li>
  </ul>
</div>

<div class="onpage-content">

<h2 id="west-nile-virus">Forecasting of Climate-Sensitive Mosquito Distributions to Evaluate Vector-Borne Disease Risk</h2>

The increased occurrence of extreme weather events is reshaping the distribution of disease vectors, increasing the risk of emerging diseases and expanding the transmission zones for pathogens such as West Nile virus (WNV). Initially, focusing on North America, we are developing a scalable framework to model and forecast the distribution of key mosquito vectors, known to be responsible for the transmission of WNV. By integrating hydrological and ecological niche modeling, landscape description and climate projections, we generate interpretable predictions of current and future habitat suitability of mosquito species.

To complement this framework, initially, we explicitly focus on *Culex pipiens pipiens* and *Culex pipiens quinquefasciatus*, two closely related, often hybridizing mosquito species. They are major vectors for WNV in North America: *C. p. pipiens* is generally found in temperate, higher-latitude regions and *C. p. quinquefasciatus* is dominant in tropical and subtropical regions. Figure 1 shows the occurrence map of *C. p. pipiens* and *C. p. quinquefasciatus* mosquito species in North America between 2020–2025. In total, 4981 occurrence records were identified.

{% include figure.html image="/assets/photos/mosquito_occurrence_map.png" alt="Occurrence map of C. p. pipiens and C. p. quinquefasciatus mosquito species in North America between 2020-2025" width="900" %}

**Figure 1:** Occurrence map of *C. p. pipiens* and *C. p. quinquefasciatus* mosquito species in North America between 2020–2025 (N=4981).

We separately modeled the habitat suitability of each mosquito species independently using MaxEnt in R and subsequently projected the habitat suitability under multiple climate change scenarios (SSP1, SSP2, SSP3, and SSP5) for the period 2070–2100. The resulting maps (Figure 2) illustrate the projected suitability of *C. p. pipiens* (CPP) and *C. p. quinquefasciatus* (CPQ) mosquitos under SSP1, SSP2, SSP3 and SSP5 scenarios, for the period 2070–2100.

{% include figure.html image="/assets/photos/mosquito_suitability_projections.png" alt="Projected suitability of C. p. pipiens and C. p. quinquefasciatus under SSP1-SSP5 climate scenarios 2070-2100" width="900" %}

**Figure 2:** Projected suitability of *C. p. pipiens* (CPP) and *C. p. quinquefasciatus* (CPQ) mosquitos under SSP1, SSP2, SSP3 and SSP5 scenarios, for the period 2070–2100.

By integrating these projections with the 2022 county-level Social Vulnerability Index (SVI) across USA (Figure 3), this approach provides foundation and support for climate-informed public health planning through early warning systems, targeted vector surveillance, and adaptive control strategies.

{% include figure.html image="/assets/photos/mosquito_svi_overlay.png" alt="Overlay of C. p. quinquefasciatus habitat suitability under SSP5 with Social Vulnerability Index USA 2022" width="900" %}

**Figure 3:** Overlay of *C. p. quinquefasciatus* projection of its habitat suitability under climate change scenario SSP5 (2070–2100) with the Social Vulnerability Index for USA in 2022.

<br><hr><br>

<h2 id="chagas-disease">Tracking the Hidden Spread: Predicting Chagas Disease Risk Through Triatomine Habitat Models in North America</h2>

Triatomines (kissing bugs) are the primary vectors responsible for spreading the parasite *Trypanosoma cruzi* that cause Chagas disease. We present a new curated dataset of triatomine observations in the Americas containing 24,933 observations sourced from literature, citizen science, and new unpublished data. The entire dataset contains 127 species, of which 35 species are from North America and represent 62.0% of the data reported here. After cleaning and filtering, data from 14 species in North America were identified to have sufficient observations for calculating habitat suitability maps (HSMs) and projecting species distributions under different climate change scenarios. Our HSMs support the endemicity of Chagas Disease in the USA and the potential for spread into Canada towards the end of this century. This curated collection of triatomines and HSMs can assist in understanding potential exposure risks and guide ongoing screening strategies for Chagas disease in North America.

{% include figure.html image="/assets/photos/workflow_habitatsuitability_chagas.png" alt="Workflow for Development of Habitat Suitability Maps of Each Kissing Bug Species" width="900" %}

**Figure 4:** Workflow for Development of Habitat Suitability Maps of Each Kissing Bug (Triatomine) Species in Current and Future Climate Scenarios.

{% include figure.html image="/assets/photos/geospatialhabitatdist_chagas.png" alt="Geospatial Habitat Distribution of 16 Predominant Kissing Bug Species in North America" width="900" %}

**Figure 5:** Geospatial Habitat Distribution of 16 Predominant Kissing Bug Species in North America.

---

{% include button.html text="Back to Research" link="/research_page/" %}

</div>
</div>

<script>
  const sections = document.querySelectorAll('.onpage-content h2[id]');
  const navLinks = document.querySelectorAll('.onpage-nav a');

  // Smooth scroll on click
  navLinks.forEach(link => {
    link.addEventListener('click', function(e) {
      e.preventDefault();
      const target = document.querySelector(this.getAttribute('href'));
      if (target) target.scrollIntoView({ behavior: 'smooth', block: 'start' });
    });
  });

  // Highlight active section on scroll
  const observer = new IntersectionObserver(entries => {
    entries.forEach(entry => {
      if (entry.isIntersecting) {
        navLinks.forEach(link => link.classList.remove('active'));
        const active = document.querySelector('.onpage-nav a[href="#' + entry.target.id + '"]');
        if (active) active.classList.add('active');
      }
    });
  }, { rootMargin: '0px 0px -60% 0px', threshold: 0 });

  sections.forEach(section => observer.observe(section));
</script>
