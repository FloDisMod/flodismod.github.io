---
title: FloDisMod
feature_text: 
  Turning the Tide on Decision Support Systems
feature_image: "/assets/cover_photo/IMG_8231-2.png"
feature_credit: Photo by Manuel Trevino
---
<br>

FloDisMod is a framework for flood and disease modeling. Initially we are focusing on the transborder region between South Texas and Mexico, with the view of expanding to the rest of the world’s coastlines. We work on understanding the dynamics of relationships between emerging infectious diseases and extreme weather. Our team includes flood, infectious disease, ecological, and geospatial experts. Our work also includes community engagement that involves a wide range of outreach activities and opportunities for mutual feedback that informs our models and ensures that the work we do targets local needs.

Please explore this website to learn more about us and our work.

<!--
<div style="text-align: center; margin-top: 2em;">
  <a href="/groups/" style="background-color: #007BFF; color: white; padding: 0.75em 1.5em; text-decoration: none; border-radius: 5px; font-weight: bold; font-size: 1.2em;">
    Meet Our Team
  </a>
</div>
-->

<br>
##### Featured Work

<style>
  .featured-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 16px;
    margin-top: 1.5rem;
  }

  .grid-item {
    position: relative;
    overflow: hidden;
    border-radius: 12px;
    background: #111;
    min-height: 240px;
  }

  .grid-item img,
  .grid-item iframe,
  .grid-item video {
    width: 100%;
    height: 100%;
    display: block;
    border: 0;
    object-fit: cover;
  }

  .span-2 {
    grid-column: span 2;
  }

  .span-3 {
    grid-column: span 3;
  }

  .short-video iframe {
    aspect-ratio: 9 / 16;
    width: 100%;
    height: 100%;
    min-height: 160px;
  }

  .caption {
    position: absolute;
    left: 0;
    right: 0;
    bottom: 0;
    padding: 0.75rem 1rem;
    background: linear-gradient(to top, rgba(0,0,0,0.72), rgba(0,0,0,0));
    color: #fff;
    font-size: 0.95rem;
    line-height: 1.3;
  }

  @media (max-width: 900px) {
    .featured-grid {
      grid-template-columns: repeat(2, 1fr);
    }

    .span-3 {
      grid-column: span 2;
    }
  }

  @media (max-width: 640px) {
    .featured-grid {
      grid-template-columns: 1fr;
    }

    .span-2,
    .span-3 {
      grid-column: span 1;
    }
  }
</style>

<div class="featured-grid">

  <!-- Clint interview video: 2 columns -->
  <div class="grid-item span-2">
    {% include video_0409.html title="Interview with Dr. Clint Dawson" %}
  </div>

  <!-- Storm rendering image: 1 column -->
  <div class="grid-item">
    <img src="/assets/photos/Beaumont_Storm_082024.jpg" alt="Storm rendering in Beaumont">
  </div>

  <!-- Shadow Watch iframe: 3 columns -->
  <div class="grid-item span-3" style="min-height: 500px;">
    <iframe
      src="https://chl.crc.nd.edu/interactive-viewer"
      title="Shadow Watch Interactive Viewer"
      loading="lazy"
      referrerpolicy="strict-origin-when-cross-origin">
    </iframe>
  </div>

  <!-- Spanish video -->
  <div class="grid-item short-video" style="min-height: 160px;">
    <iframe
      src="https://www.youtube.com/embed/1x1HDqH8F_A"
      title="FloDisMod video in Spanish"
      allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
      allowfullscreen>
    </iframe>
  </div>

  <!-- Brian Stokes bird photo: 2 columns -->
  <div class="span-2" style="display: flex; flex-direction: column; gap: 6px;">
    <div class="grid-item" style="min-height: 160px; flex: 1;">
      <img src="/assets/photos/brian_stokes_bird.jpg" alt="Photo by Brian Stokes">
    </div>
    <div style="color: #000; font-size: 0.8rem; padding: 2px 4px;">Photo: Brian Stokes</div>
  </div>

  <!-- Eclipse placeholder: full width -->
  <div class="grid-item span-3">
    <img src="/assets/photos/eclipse_still_harvey.jpg" alt="Eclipse event placeholder">
  </div>

</div>

<br>
##### Research
{% include display-research.html %}

<!--
<br>
##### Latest Post from NEWS & OUTREACH
{% include try_blog.html %}
-->