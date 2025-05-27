---
layout: page
title: Meet the Organizers
permalink: /organizers/
---

Sleek is a modern Jekyll theme focused on speed performance & SEO best practices. You can find out more info about customizing your Jekyll theme, as well as basic Jekyll usage documentation at [jekyllrb.com](http://jekyllrb.com/) or simply read the guide on how to [get started](/getting-started)

<!-- =====  Speaker section  ===== -->
<style>
/* --- layout --- */
.speaker-section { text-align: center; font-family: system-ui, sans-serif; }
.speaker-grid    { display: flex; flex-wrap: wrap; gap: 2rem; justify-content: center; margin-top: 2rem; }

/* --- individual card --- */
.speaker-card {
  background: #fff;
  width: 220px;                /* tweak width as needed */
  border-radius: 1rem;
  box-shadow: 0 4px 12px rgba(0,0,0,.07);
  transition: transform .2s ease, box-shadow .2s ease;
}
.speaker-card:hover {          /* optional little hover lift */
  transform: translateY(-4px);
  box-shadow: 0 8px 16px rgba(0,0,0,.10);
}

/* --- card contents --- */
.speaker-card img {
  width: 100%;
  height: 240px;               /* keep faces equally tall */
  object-fit: cover;
  border-top-left-radius: 1rem;
  border-top-right-radius: 1rem;
}

.speaker-name  { font-weight: 700; font-size: 1.1rem; margin: 1rem .75rem .35rem; }
.speaker-affil { color: #0081cb; font-weight: 600; font-size: .9rem; margin-bottom: 1.25rem; }
</style>

<div class="speaker-section">
  <h2>Invited Speakers</h2>

  <div class="speaker-grid">
    <!-- Speaker 1 -->
    <div class="speaker-card">
      <img src="" alt="Ndapewa Onyothi Wilhelmina Nekoto" />
      <div class="speaker-name">Ndapewa Onyothi<br>Wilhelmina Nekoto</div>
      <div class="speaker-affil">Namibia / Masakhane</div>
    </div>

<!-- Speaker 2 -->
<div class="speaker-card">
    <img src="{{ site.url }}{{ site.baseurl }}/assets/img/organizer/wiebke.jpg" alt="Wiebke" />
    <div class="speaker-name">Dr. Chinasa T. Okolo</div>
    <div class="speaker-affil">Brookings Institution</div>
</div>

<!-- Speaker 3 -->
<div class="speaker-card">
    <img src="https://placehold.co/400x400" alt="Leonida Mutuku" />
    <div class="speaker-name">Leonida Mutuku</div>
    <div class="speaker-affil">LDRI</div>
</div>

<!-- Speaker 4 -->
<div class="speaker-card">
    <img src="https://placehold.co/400x400" alt="Dr. Lilian Wanzare" />
    <div class="speaker-name">Dr. Lilian Wanzare</div>
    <div class="speaker-affil">Maseno University</div>
</div>

<!-- Speaker 5 -->
<div class="speaker-card">
    <img src="https://placehold.co/400x400" alt="Chloe Burke" />
    <div class="speaker-name">Chloe Burke</div>
    <div class="speaker-affil">Meta</div>
</div>
</div>
</div>
