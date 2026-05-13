---
title: Model Flooding and Storm Surges
feature_text: |
  Research

feature_image: "/assets/cover_photo/pier.png"
feature_credit: Photo by Dr. Tamer Oraby

---

<style>
.flood-h2 {
  font-size: 1.3rem;
  font-weight: normal;
  border-bottom: 1px solid #ddd;
  padding-bottom: 0.3rem;
  margin: 2.2rem 0 0.9rem;
  color: #111;
  font-family: Helvetica, sans-serif;
}
.flood-h3 {
  font-size: 1.05rem;
  font-weight: bold;
  margin: 1.6rem 0 0.5rem;
  color: #222;
  font-family: Helvetica, sans-serif;
}
.flood-p {
  font-family: Helvetica, sans-serif;
  font-size: 15px;
  line-height: 1.7;
  color: #333;
  margin: 0 0 1rem;
}
.flood-table {
  width: 100%;
  border-collapse: collapse;
  font-size: 0.88rem;
  margin: 1rem 0 1.5rem;
  font-family: Helvetica, sans-serif;
}
.flood-table th {
  background: #f4f4f4;
  text-align: left;
  padding: 0.5rem 0.75rem;
  border: 1px solid #ddd;
  font-weight: bold;
  font-size: 0.83rem;
}
.flood-table td {
  padding: 0.45rem 0.75rem;
  border: 1px solid #ddd;
  vertical-align: top;
  font-family: Helvetica, sans-serif;
}
.flood-table tr:nth-child(even) td { background: #fafafa; }

.flood-paper {
  border-left: 3px solid #bf5700;
  padding: 0.75rem 1rem;
  margin: 1.2rem 0;
}
.flood-paper .flood-paper-title {
  font-weight: bold;
  font-size: 0.98rem;
  color: #111;
  margin-bottom: 0.2rem;
  font-family: Helvetica, sans-serif;
}
.flood-paper .flood-paper-title a,
.flood-paper .flood-paper-title a:link,
.flood-paper .flood-paper-title a:visited {
  color: #bf5700 !important;
  background-image: none !important;
  box-shadow: none !important;
  text-shadow: none !important;
  border-bottom: none !important;
}
.flood-paper .flood-paper-title a:hover {
  text-decoration: underline !important;
}
.flood-paper .flood-paper-meta {
  font-size: 0.84rem;
  color: #666;
  font-style: italic;
  margin-bottom: 0.5rem;
  font-family: Helvetica, sans-serif;
}
.flood-paper .flood-paper-body {
  font-size: 0.91rem;
  color: #333;
  line-height: 1.6;
  font-family: Helvetica, sans-serif;
  margin: 0 0 0.6rem;
}
.flood-refs {
  font-size: 0.87rem;
  color: #444;
  padding-left: 1.5rem;
  font-family: Helvetica, sans-serif;
  line-height: 1.6;
}
.flood-refs li { margin-bottom: 0.5rem; }
.flood-footer {
  margin-top: 2.5rem;
  padding-top: 1rem;
  border-top: 1px solid #ccc;
  font-size: 0.82rem;
  color: #555;
  font-family: Helvetica, sans-serif;
  line-height: 1.6;
}
.flood-disclaimer {
  margin-top: 0.8rem;
  font-size: 0.78rem;
  color: #777;
  font-style: italic;
}
</style>

<br>

<div style="display: flex; flex-direction: column; align-items: center;">
  <div style="width: 840px; max-width: 100%;">
    <div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden;">
      <iframe src="https://www.youtube.com/embed/A5MptxF9xpw?si=SDLAkS3a_UlqrRpR"
        title="Dr. Clint Dawson on Storm Surge Modeling"
        frameborder="0"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
        referrerpolicy="strict-origin-when-cross-origin"
        allowfullscreen
        style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;">
      </iframe>
    </div>
    <p style="font-family: Helvetica, sans-serif; font-size: 13px; color: #555; margin-top: 0.4rem;"><em>Dr. Clint Dawson discusses the group's research on data-driven storm surge modeling, recognized with the 2024 University of Texas at Austin President's Research Impact Award.</em></p>
  </div>
</div>

<h2 class="flood-h2">Overview</h2>

<p class="flood-p">When a tropical storm or hurricane approaches a coastline, the strong winds blowing over the ocean's surface push water towards the shore, resulting in storm surge — a sudden and abnormal rise in sea level. Storm surge is especially dangerous because it can cause widespread flooding, destruction of infrastructure, significant economic damage, and loss of life. As in any natural hazard scenario, the safety of a community is directly tied to the ability of forecasters to successfully predict the location and timing of storm surge and respond. Accurate modeling is invaluable in the planning processes both far out and near the time of a severe storm event [1].</p>

<p class="flood-p">Our research in particular focuses on the resulting compound flooding associated with this natural hazard. Flooding and standing water can be a problem contributing to the breeding of disease-carrying insects such as Kissing Bugs [2] and mosquitoes due to the impact it has on their habitat and the increased availability of suitable breeding sites.</p>

<h2 class="flood-h2">ADCIRC Model</h2>

<p class="flood-p">To perform our research studies, we actively develop and apply the <a href="https://www.adcirc.org">Advanced Circulation Model (ADCIRC)</a> [3], which has been extensively used for storm surge and flood forecasting. It has been applied to numerous real-world scenarios, including hurricane impact assessments, emergency response planning, and coastal infrastructure design [1]. Its accuracy and reliability have been established through rigorous comparisons with observational data from previous storms [1], rendering it an indispensable tool for coastal communities and researchers studying coastal dynamics.</p>

<p class="flood-p">ADCIRC is a finite element model that employs mathematical equations to simulate the intricate behavior of water, incorporating factors such as wind, seafloor bathymetry, and coastline features [4]. It utilizes powerful high-performance computer simulations to model the immense power of the ocean in extreme weather conditions.</p>

<p class="flood-p">Since 2006, ADCIRC has been used for event-based forecasting during hurricane events. PI Dawson and Co-PI Valseth are, and have been, involved in projects developing such forecasts, including the Coastal Emergency Risks Assessment (CERA) tool at <a href="https://cera.coastalrisk.live">cera.coastalrisk.live</a>.</p>

<h3 class="flood-h3">ADCIRC Model Skill</h3>

<p class="flood-p">NOAA's operational <strong>STOFS-2D-Global</strong> model is built on ADCIRC and is to date the most accurate published non-data-assimilated global tidal model [5, 6]. The table below summarizes its baseline skill. Station-level improvements from coupling with a Temporal Fusion Transformer are shown in the AI Research section below [7].</p>

<table class="flood-table">
  <thead>
    <tr>
      <th>Evaluation</th>
      <th>Stations</th>
      <th>R²</th>
      <th>Mean Amp. Error</th>
      <th>NRMSE</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>M₂ tide — deep ocean</td>
      <td>236</td>
      <td>0.985</td>
      <td>2.4 cm</td>
      <td>0.075</td>
    </tr>
    <tr>
      <td>M₂ tide — continental shelf</td>
      <td>449</td>
      <td>0.984</td>
      <td>4.3 cm</td>
      <td>0.084</td>
    </tr>
    <tr>
      <td>Total water level — US NOS stations (multiyear hindcast)</td>
      <td>228</td>
      <td>0.94</td>
      <td>7.3 cm</td>
      <td>0.21</td>
    </tr>
  </tbody>
</table>

<h2 class="flood-h2">AI Research</h2>

<p class="flood-p">Alongside high-fidelity physics simulation, our group has developed a progressive line of AI-driven research — from fast machine learning surrogates for peak surge prediction, to transformer-based forecast correction, to autonomous multi-agent systems that reason over the entire coastal data ecosystem.</p>

<div class="flood-paper">
  <div class="flood-paper-title"><a href="https://doi.org/10.1016/j.coastaleng.2023.104406">A Framework for Flexible Peak Storm Surge Prediction</a></div>
  <div class="flood-paper-meta">Pachev, Arora, del-Castillo-Negrete, Valseth &amp; Dawson — <em>Coastal Engineering</em>, Vol. 186, 2023, 104406</div>
  <p class="flood-paper-body">Develops a surrogate model for peak storm surge prediction using a two-stage approach: first classifying whether a point will be inundated, then predicting the level of inundation. A key innovation is a point-based formulation that enables predictions at locations not present in the training data, significantly reducing the number of required model parameters. Demonstrated on the Texas coast (446 synthetic hurricanes; validated on Ike 2008 and Harvey 2017) and the northern Alaskan coast (109 historical events; tested on Typhoon Merbok 2022). The surrogate models are many orders of magnitude faster than ADCIRC while maintaining comparable accuracy against observational data.</p>
</div>

<div class="flood-paper">
  <div class="flood-paper-title"><a href="https://doi.org/10.1016/j.ocemod.2025.102509">Correcting Physics-Based Global Tide and Storm Water Level Forecasts with the Temporal Fusion Transformer</a></div>
  <div class="flood-paper-meta">Cerrone, Westerink, Ling, Blakely, Wirasaet, Dawson &amp; Westerink — <em>Ocean Modelling</em>, Vol. 195, 2025, 102509</div>
  <p class="flood-paper-body">Rather than replacing ADCIRC, this work weakly couples the Temporal Fusion Transformer (TFT) to NOAA's STOFS-2D-Global operational model to correct its forecasts over a 7-day horizon at 228 NOAA water level stations. The TFT is trained on a 3-year ADCIRC hindcast (2016–2019) to learn patterns in model error space — correcting tidal phasing errors at tidally-dominant stations and wind-driven biases at wind-dominant stations. Results show notable improvements in Alaska, the Atlantic seaboard, and the Pacific seaboard.</p>
  <p class="flood-paper-body">Representative station-level improvements (ADCIRC alone vs. ML-corrected ADCIRC):</p>
  <table class="flood-table">
    <thead>
      <tr>
        <th>Station</th>
        <th>Type</th>
        <th>NRMSE (ADCIRC)</th>
        <th>NRMSE (ML-Corrected)</th>
        <th>R² improvement</th>
      </tr>
    </thead>
    <tbody>
      <tr><td>Boston, MA</td><td>Tidal</td><td>0.116</td><td>0.062</td><td>0.986 → 0.996</td></tr>
      <tr><td>Anchorage, AK</td><td>Tidal</td><td>0.173</td><td>0.059</td><td>0.970 → 0.997</td></tr>
      <tr><td>Annapolis, MD</td><td>Wind-dominant</td><td>0.223</td><td>0.176</td><td>0.912 → 0.943</td></tr>
      <tr><td>Baltimore, MD</td><td>Wind-dominant</td><td>0.280</td><td>0.210</td><td>0.886 → 0.936</td></tr>
      <tr><td>Bridesburg, PA</td><td>Riverine</td><td>0.339</td><td>0.114</td><td>0.875 → 0.986</td></tr>
      <tr><td>Pilottown, LA</td><td>Wind-dominant</td><td>0.748</td><td>0.130</td><td>0.736 → 0.918</td></tr>
    </tbody>
  </table>
  <p class="flood-paper-body">Across all 228 stations: 90% of tidal stations saw NRMSE decrease by at least 25%; 50% saw it halved. At wind-dominant stations, 40% saw NRMSE decrease by at least 25%. Late-horizon degradation (day 6–7 vs. day 0–1) never exceeded 25% of a station's average NRMSE.</p>
</div>

<div class="flood-paper">
  <div class="flood-paper-title"><a href="https://arxiv.org/abs/2605.01102">Towards Multi-Agent Autonomous Reasoning in Hydrodynamics</a></div>
  <div class="flood-paper-meta">Zhao, Cerrone, Westerink &amp; Dawson — <em>arXiv preprint</em>, arXiv:2605.01102, May 2026</div>
  <p class="flood-paper-body">Presents a multi-agent system (MAS) prototype for hydrodynamics in which specialized LLM agents are coordinated through a dynamically constructed Layer Execution Graph (LEG). A Graph Architect agent parses natural-language queries and builds query-specific execution topologies; specialist agents (NHC, NOAA CO-OPS, USGS, FEMA, STOFS, OSM) retrieve data from authoritative federal sources; Consolidator agents compress parallel outputs to prevent context saturation; and a Reporter synthesizes the final answer. Evaluated on 37 queries across six complexity categories using Claude Sonnet 4.6 as the backbone LLM, the prototype achieves 93.6% factual precision with a 100% pass rate and zero hallucinations on adversarial inputs.</p>
</div>

<h2 class="flood-h2">References</h2>

<ol class="flood-refs">
  <li>Dawson, C. and Proft, J. (2012). Predicting Storm Surge. In P. Bedient (Ed.), <em>Lessons From Hurricane Ike</em>, pp. 50–65. Texas A&amp;M University Press.</li>
  <li>FloDisMod website: <a href="https://www.flodismod.com">www.flodismod.com</a></li>
  <li>ADCIRC: <a href="https://www.adcirc.org">www.adcirc.org</a></li>
  <li>Bunya, S., Dietrich, J., Westerink, J., Ebersole, B., Smith, J., Atkinson, J., Jensen, R., Resio, D., Luettich, R., Dawson, C. et al. (2010). A high resolution coupled riverine flow, tide, wind, wind wave and storm surge model for southern Louisiana and Mississippi: part I — model development and validation. <em>Monthly Weather Review</em>, 138(2), 345–77.</li>
  <li>Stammer, D. et al. (2014). Accuracy assessment of global barotropic ocean tide models. <em>Reviews of Geophysics</em>, 52(3), 243–282.</li>
  <li>Blakely, C.P. et al. (2022). Dissipation and bathymetric sensitivities in an unstructured mesh global tidal model. <em>Journal of Geophysical Research: Oceans</em>, 127(5).</li>
  <li>Cerrone, A.R., Westerink, L.G., Ling, G., Blakely, C.P., Wirasaet, D., Dawson, C., &amp; Westerink, J.J. (2025). Correcting physics-based global tide and storm water level forecasts with the temporal fusion transformer. <em>Ocean Modelling</em>, 195, 102509. <a href="https://doi.org/10.1016/j.ocemod.2025.102509">https://doi.org/10.1016/j.ocemod.2025.102509</a></li>
  <li>Pachev, B., Arora, P., del-Castillo-Negrete, C., Valseth, E., &amp; Dawson, C. (2023). A framework for flexible peak storm surge prediction. <em>Coastal Engineering</em>, 186, 104406. <a href="https://doi.org/10.1016/j.coastaleng.2023.104406">https://doi.org/10.1016/j.coastaleng.2023.104406</a></li>
  <li>Zhao, J., Cerrone, A., Westerink, J., &amp; Dawson, C. (2026). Towards multi-agent autonomous reasoning in hydrodynamics. <em>arXiv preprint</em> arXiv:2605.01102. <a href="https://arxiv.org/abs/2605.01102">https://arxiv.org/abs/2605.01102</a></li>
</ol>

<div class="flood-footer">
  <div>This work is supported by Wellcome Trust, Planet Texas 2050, Texas Water Development Board (TWDB Contract No. 2201792620), and NSF-PREEVENTS (1855047).</div>
  <div style="margin-top:0.3rem;">University of Texas at Austin · UTRGV</div>
  <div style="margin-top:0.6rem;">
    Project Manager Dr. Chrysoula Panethymitaki: <a href="mailto:chrysoula@austin.utexas.edu">chrysoula@austin.utexas.edu</a> ·
    Project Lead Dr. Katherine Brown: <a href="mailto:kate01@mail.utexas.edu">kate01@mail.utexas.edu</a>
  </div>
  <div class="flood-disclaimer">Please check with your regional National Weather Service office for the official water level forecast. For official storm surge information associated with tropical cyclones, please consult advisories and warnings issued by the National Hurricane Center. For infectious disease information, please consult your local public health authorities. All rights reserved. © The University of Texas at Austin 2026.</div>
</div>

{% include button.html text="Back" link="/research_page/" %}
