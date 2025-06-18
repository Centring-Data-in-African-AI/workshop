---
layout: page
title: Speakers
permalink: /speakers/
---
<style>
.speakers {
  display: flex;
  flex-direction: column;
  gap: 2rem;
  max-width: 900px;
  margin: 0 auto;
  padding: 1rem;
}

.speaker-card {
  display: flex;
  background: #fff;
  border-radius: 1rem;
  box-shadow: 0 4px 12px rgba(0,0,0,.07);
  overflow: hidden;
  transition: transform .2s ease, box-shadow .2s ease;
}
.speaker-card:hover {
  transform: translateY(-3px);
  box-shadow: 0 8px 16px rgba(0,0,0,.10);
}

.speaker-left {
  flex: 0 0 220px;      /* fixed width for image + text */
  text-align: center;
  border-right: 1px solid #eee;
}

.speaker-left img {
  width: 100%;
  height: 240px;
  object-fit: cover;
  /* round the top‐left and bottom‐left corners */
  border-top-left-radius: 1rem;
  border-bottom-left-radius: 1rem;
}

.speaker-name {
  margin: 0.75rem 0 0.25rem;
  font-weight: 700;
  font-size: 1.2rem;
}

.speaker-affil {
  margin: 0 0 1rem;
  font-weight: 600;
  color: #0081cb;
  font-size: 0.95rem;
  padding: 0 0.5rem;
}

.speaker-right {
  flex: 1;
  padding: 1.5rem;
}

.speaker-bio {
  margin: 0;
  font-size: 0.95rem;
  line-height: 1.6;
  color: #333;
  text-align: left;
}

/* Mobile: stack into single column */
@media (max-width: 600px) {
  .speaker-card {
    flex-direction: column;
  }
  .speaker-left {
    flex: none;
    border-right: none;
    border-bottom: 1px solid #eee;
  }
  .speaker-right {
    padding: 1rem;
  }
}
</style>


<section class="speakers">

  <!-- Speaker #1 -->
  <div class="speaker-card">
    <div class="speaker-left">
      <img src="…/img/speaker1.jpg" alt="Speaker One">
      <div class="speaker-name">Speaker One</div>
      <div class="speaker-affil">Chief Data Scientist, Acme AI</div>
    </div>
    <div class="speaker-right">
      <p class="speaker-bio">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. 
        Donec a semper urna, vitae luctus magna. Praesent tempor 
        sapien nec risus scelerisque, a feugiat libero pretium.
      </p>
    </div>
  </div>

  <!-- Speaker #2 -->
  <div class="speaker-card">
    <div class="speaker-left">
      <img src="…/img/speaker2.jpg" alt="Speaker Two">
      <div class="speaker-name">Speaker Two</div>
      <div class="speaker-affil">Director of Research, Globex Labs</div>
    </div>
    <div class="speaker-right">
      <p class="speaker-bio">
        Vivamus euismod, justo non dignissim luctus, ex erat commodo 
        velit, ut suscipit enim lectus non purus. Sed vitae risus at 
        nunc ultrices interdum.
      </p>
    </div>
  </div>

</section>
