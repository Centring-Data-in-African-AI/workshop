---
layout: page
title: Meet the Organisers
permalink: /organizers/
---

The organising team for this workshop has rich and varied collective experience in the African data ecosystem, and in working with African communities. Team members have worked on many technical and socio-technical aspects of data for AI, spanning data collection, crowdsourcing and annotation, data publishing, management, sharing and governance.

<!-- =====  Speaker section  ===== -->
<style>
  /* --- top‐level container; no longer wraps all cards as one flexbox --- */
  .speaker-section {
    text-align: center;
    font-family: system-ui, sans-serif;
  }

  /* --- each “row” is a flex container on its own --- */
.speaker-row {
  display: flex;
  flex-direction: row;      /* horizontal by default */
  justify-content: center;
  gap: 2rem;
  margin-top: 2rem;
}

  /* --- individual card styling (same as before) --- */
  .speaker-card {
    background: #fff;
    width: 220px;                /* tweak width as needed */
    border-radius: 1rem;
    box-shadow: 0 4px 12px rgba(0, 0, 0, .07);
    transition: transform .2s ease, box-shadow .2s ease;
  }
  .speaker-card:hover {
    transform: translateY(-4px);
    box-shadow: 0 8px 16px rgba(0, 0, 0, .10);
  }

  .speaker-card img {
    width: 100%;
    height: 240px;               /* keep faces equally tall */
    object-fit: cover;
    border-top-left-radius: 1rem;
    border-top-right-radius: 1rem;
  }

  .speaker-name {
    font-weight: 700;
    font-size: 1.1rem;
    margin: 1rem .75rem .35rem;
  }
  .speaker-affil {
    color: #0081cb;
    font-weight: 600;
    font-size: .9rem;
    margin-bottom: 1.25rem;
  }


@media (max-width: 600px) {
  /* Stack each row’s cards vertically */
  .speaker-row {
    flex-direction: column;
    gap: 1.5rem;
    margin-top: 1.5rem;
  }

  /* Allow each card to expand full‐width on mobile */
  .speaker-card {
    width: 100%;
    max-width: 360px;    /* optional cap */
    margin: 0 auto;
  }

  /* Let the image scale naturally */
  .speaker-card img {
    height: auto;
    aspect-ratio: 4/5;
  }
}



</style>

<div class="speaker-section">

  <!-- ===== Row 1: exactly 3 speakers ===== -->
  <div class="speaker-row">
    <!-- Org 1 -->
    <div class="speaker-card">
      <img src="{{ site.url }}{{ site.baseurl }}/assets/img/organizer/wiebke.jpg" alt="Dr Wiebke Hutiri" />
      <div class="speaker-name">Dr Wiebke Hutiri</div>
      <div class="speaker-affil">Research Scientist, Sony AI, Switzerland</div>
    </div>

  <!-- Org 2 -->
  <div class="speaker-card">
    <img src="{{ site.url }}{{ site.baseurl }}/assets/img/organizer/SMHall.jpg" alt="Siobhan Mackenzie Hall" />
    <div class="speaker-name">Siobhan Mackenzie Hall</div>
    <div class="speaker-affil">DPhil Student, University of Oxford</div>
  </div>

  <!-- Org 3 -->
  <div class="speaker-card">
    <img src="{{ site.url }}{{ site.baseurl }}/assets/img/organizer/rae_rae.png" alt="Raesetje Sefala" />
    <div class="speaker-name">Raesetje Sefala</div>
    <div class="speaker-affil">PhD Student at McGill University and Mila, Research Fellow at DAIR Institute, Canada</div>
  </div>
  </div>



  <!-- ===== Row 3: exactly 4 speakers ===== -->
  <div class="speaker-row">
    <!-- Org 7 -->
    <div class="speaker-card">
      <img src="{{ site.url }}{{ site.baseurl }}/assets/img/organizer/Thapelo.jpg" alt="Thapelo Andrew Sindane" />
      <div class="speaker-name">Thapelo Andrew Sindane</div>
      <div class="speaker-affil">PhD Candidate, Computer Science, University of Pretoria</div>
    </div>

<!-- Org 4 -->
  <div class="speaker-card">
    <img src="{{ site.url }}{{ site.baseurl }}/assets/img/organizer/jess.jpeg" alt="Jessica Ojo" />
    <div class="speaker-name">Jessica Ojo</div>
    <div class="speaker-affil">Research Engineer, Lelapa.ai; Research Student at McGill University and Mila, Canada</div>
  </div>

  <!-- Org 5 -->
  <div class="speaker-card">
    <img src="{{ site.url }}{{ site.baseurl }}/assets/img/organizer/aremu.jpg" alt="Aremu Anuoluwapo" />
    <div class="speaker-name">Aremu Anuoluwapo</div>
    <div class="speaker-affil">Lead Data Officer, Lelapa.ai; MSc. Student at University of Trento, Italy</div>
  </div>

  <!-- Org 6 -->
  <div class="speaker-card">
    <img src="{{ site.url }}{{ site.baseurl }}/assets/img/organizer/chris emezue.jpg" alt="Chris Emezue" />
    <div class="speaker-name">Chris Emezue</div>
    <div class="speaker-affil">Founder & Executive Director at Lanfrica Labs; Researcher at Mila, Canada</div>
  </div>

  </div>

</div>

  <!-- ===== Acknowledgment Section ===== -->
  <div style="margin-top: 4rem; text-align: center;">
    <!-- <h2 style="margin-bottom: 2rem; color: #333; font-family: system-ui, sans-serif;">Special Acknowledgment</h2> -->
    
    <div style="display: flex; justify-content: center; margin-top: 2rem;">
      <div class="speaker-card" style="display: flex; align-items: flex-start; margin: 0; max-width: 900px; width: 100%; background: none; box-shadow: none; gap: 2rem;">
        <img src="{{ site.url }}{{ site.baseurl }}/assets/img/Shaimaa-Lazem-lbw-chair.jpg" alt="Prof Shaimaa" style="height: 320px; width: 240px; object-fit: cover; border-radius: 0.5rem; flex-shrink: 0;" />
        <div style="text-align: left; flex: 1; min-width: 0;">
          <div class="speaker-name" style="margin-top: 0; margin-bottom: 1rem;">Prof Shaimaa Lazem</div>
          <div style="padding: 0; font-size: 0.9rem; line-height: 1.6; color: #666; overflow-x: auto; white-space: normal;">
            Shaimaa Lazem is an Associate Research Professor at the City of Scientific Research and Technological Applications (SRTA-City), Egypt. Her PhD in Computer Science from Virginia Tech, USA, fueled her passion for understanding how technology design can transcend Western perspectives. Dr. Lazem champions the development of inclusive and impactful technologies. She leverages participatory design methods and critical approaches like decolonial and feminist theories to ensure technology serves everyone effectively. She is working on developing human-centered approaches to design Natural Language Processing (NLP) applications in Africa with support from Google 2020 Award for Inclusion Research and Google AI 2021 Award. She was Recognized as <a href="https://www.acm.org/articles/people-of-acm/2023/shaimaa-lazem" target="_blank">People of ACM in 2023</a> and a Leaders-in-Innovation Fellow with the Royal Academy of Engineering in London since 2018.
          </div>
        </div>
      </div>
    </div>
  </div>


