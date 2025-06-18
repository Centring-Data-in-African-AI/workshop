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
      <img src="{{ site.url }}{{ site.baseurl }}/assets/img/speaker/girmaw.png" alt="Dr. Girmaw Abebe Tadesse">
      <div class="speaker-name">Dr. Girmaw Abebe Tadesse</div>
      <div class="speaker-affil">Principal Research Scientist and Manager at Microsoft AI for Good Lab</div>
    </div>
    <div class="speaker-right">
      <p class="speaker-bio">
        Dr. Girmaw Abebe Tadesse is a Principal Research Scientist and Manager at Microsoft's AI 
for Good Research Lab, where he leads the Africa team in developing AI solutions for 
agriculture, healthcare, biodiversity, and more. He collaborates with a diverse range of 
partners, including governments, non-profits, academic institutions, and startups. He holds 
over 20 U.S. patents, and his work has received Best Paper Awards at conferences, been 
published in leading journals such as Nature, and featured by media outlets including the 
BBC. He is an active program committee member and speaker at global AI conferences, 
including ICLR 2023 (Kigali), ICLR 2024 (Vienna), IJCAI 2024 (Jeju), and ICCV 2024 (Paris).
He previously worked as a Staff Research Scientist at IBM Research Africa and as a 
Postdoctoral Researcher at the University of Oxford. He earned his PhD from Queen Mary 
University of London through the Erasmus Mundus Double Doctorate Program.
      </p>
    </div>
  </div>

  <!-- Speaker #2 -->
  <div class="speaker-card">
    <div class="speaker-left">
      <img src="{{ site.url }}{{ site.baseurl }}/assets/img/speaker/dla.jpg" alt="Data Labelers Association">
      <div class="speaker-name">Data Labelers Association</div>
      <!-- <div class="speaker-affil">Director of Research, Globex Labs</div> -->
    </div>
    <div class="speaker-right">
      <p class="speaker-bio">
        The Data Labelers Association (DLA) is a worker-led organization formed by data annotators in Kenya in response to poor working conditions and systemic neglect. DLA advocates for labor rights, better working conditions, and increased recognition of the critical role data workers play in the AI industry. Beyond organizing, DLA addresses the widespread knowledge gap about annotation work, highlighting its challenges and the toxic environments many workers face. We engage in policy and legislative spaces to shape just and effective frameworks, serving as a vital bridge between workers, government, tech companies, and legislators. As AI transforms global labor markets, DLA is claiming space to ensure data workers help shape the industry's future.
      </p>
    </div>
  </div>

</section>
