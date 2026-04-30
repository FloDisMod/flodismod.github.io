---
title: Ongoing Research
feature_text: |
  Research

feature_image: "/assets/cover_photo/pier.png"
feature_credit: Photo by Dr. Tamer Oraby

---


## Forecasting of Climate-Sensitive Mosquito Distributions to Evaluate Vector-Borne Disease Risk

The increased occurrence of extreme weather events is reshaping the distribution of disease vectors, increasing the risk of emerging diseases and expanding the transmission zones for pathogens such as West Nile virus (WNV). Initially, focusing on North America, we are developing a scalable framework to model and forecast the distribution of key mosquito vectors, known to be responsible for the transmission of WNV. By integrating hydrological and ecological niche modeling, landscape description and climate projections, we generate interpretable predictions of current and future habitat suitability of mosquito species.

To complement this framework, initially, we explicitly focus on *Culex pipiens pipiens* and *Culex pipiens quinquefasciatus*, two closely related, often hybridizing mosquito species. They are major vectors for WNV in North America: *C. p. pipiens* is generally found in temperate, higher-latitude regions and *C. p. quinquefasciatus* is dominant in tropical and subtropical regions. Figure 1 shows the occurrence map of *C. p. pipiens* and *C. p. quinquefasciatus* mosquito species in North America between 2020–2025. In total, 4981 occurrence records were identified.

{% include figure.html image="/assets/photos/mosquito_occurrence_map.png" alt="Occurrence map of C. p. pipiens and C. p. quinquefasciatus mosquito species in North America between 2020-2025" width="900" %}

**Figure 1:** Occurrence map of *C. p. pipiens* and *C. p. quinquefasciatus* mosquito species in North America between 2020–2025 (N=4981).

<br>

We separately modeled the habitat suitability of each mosquito species independently using MaxEnt in R and subsequently projected the habitat suitability under multiple climate change scenarios (SSP1, SSP2, SSP3, and SSP5) for the period 2070–2100. The resulting maps (Figure 2) illustrate the projected suitability of *C. p. pipiens* (CPP) and *C. p. quinquefasciatus* (CPQ) mosquitos under SSP1, SSP2, SSP3 and SSP5 scenarios, for the period 2070–2100.

{% include figure.html image="/assets/photos/mosquito_suitability_projections.png" alt="Projected suitability of C. p. pipiens and C. p. quinquefasciatus under SSP1-SSP5 climate scenarios 2070-2100" width="900" %}

**Figure 2:** Projected suitability of *C. p. pipiens* (CPP) and *C. p. quinquefasciatus* (CPQ) mosquitos under SSP1, SSP2, SSP3 and SSP5 scenarios, for the period 2070–2100.

<br>

By integrating these projections with the 2022 county-level Social Vulnerability Index (SVI) across USA (Figure 3), this approach provides foundation and support for climate-informed public health planning through early warning systems, targeted vector surveillance, and adaptive control strategies.

{% include figure.html image="/assets/photos/mosquito_svi_overlay.png" alt="Overlay of C. p. quinquefasciatus habitat suitability under SSP5 with Social Vulnerability Index USA 2022" width="900" %}

**Figure 3:** Overlay of *C. p. quinquefasciatus* projection of its habitat suitability under climate change scenario SSP5 (2070–2100) with the Social Vulnerability Index for USA in 2022.

<br>

{% include button.html text="Back to Research" link="/research_page/" %}
