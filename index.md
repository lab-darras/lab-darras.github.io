---
layout: default
title: Darras Lab
permalink: /
---

<style>
/* General layout */
.section{ padding:48px 0; }
.lead{ font-size:1.05rem; line-height:1.6; max-width:80ch; }

/* Research images */
.research-images{
  display:flex;
  gap:2%;
  justify-content:space-between;
  margin-top:30px;
}
.research-images img{
  width:23.5%;
  height:auto;
  object-fit:cover;
}

/* People */
.people-grid{
  display:grid;
  grid-template-columns:repeat(5, minmax(0,1fr));
  gap:18px;
  margin-top:24px;
}
@media (max-width:1050px){
  .people-grid{ grid-template-columns:repeat(3,1fr); }
}
@media (max-width:700px){
  .people-grid{ grid-template-columns:repeat(2,1fr); }
}
.person{ text-align:center; }
.avatar{
  width:110px;
  height:110px;
  object-fit:cover;
  border-radius:50%;
  box-shadow:0 4px 10px rgba(0,0,0,0.10);
}
.person .name{ margin-top:10px; font-weight:600; font-size:1.02rem; }
.person .role, .person .inst{
  font-size:0.9rem;
  line-height:1.25;
}
.person .role{ font-weight:600; }
.person .inst{ opacity:0.8; }
.person a{
  font-size:0.9rem;
  color:#0066cc;
  text-decoration:none;
}
.person a:hover{ text-decoration:underline; }

/* Banner link */
.team-banner{
  text-align:center;
  margin-top:50px;
}
.team-banner a{
  font-size:1rem;
  color:#0066cc;
  text-decoration:none;
}
.team-banner a:hover{
  color:#004999;
  text-decoration:underline;
}
</style>

<section class="section">
  <h1>Darras Lab</h1>

  <h2>Evolution of genetic systems and genomic conflicts</h2>

  <p class="lead">
    Conflicts manifest at multiple biological levels, including genomes, cells, individuals,
    and societies, yet their long-term consequences remain poorly understood. Although diverse
    forms of conflict are increasingly documented, their genomic distribution and impact on
    genome architecture remain largely unexplored, as many conflicts are transient and difficult
    to study.
  </p>

  <p>
    Our goal is to investigate the diversity of genomic conflicts, the molecular innovations
    they generate, and their effects on genome evolution. We study conflicts in ant societies,
    where reproduction is unequally distributed between queens and workers. This division of
    labor has repeatedly produced extraordinary genetic systems, in which selfish lineages
    drive their carriers to develop as reproductive queens, while the worker caste arises only
    through hybridization with another lineage.
  </p>

  <p>
    We investigate the mechanisms underlying these hybrid systems using population genomic and
    molecular approaches, focusing on the ants <em>Paratrechina longicornis</em> and
    <em>Wasmannia auropunctata</em>, where queens and males belong to divergent clonal lineages;
    the ant <em>Anoplolepis gracilipes</em>, where males are chimeras carrying divergent genomes
    in different cells of their body; and <em>Cataglyphis</em> ants, where two queen lineages
    coexist within populations and must hybridize to produce workers. These unique systems
    provide opportunities to study conflicts and investigate how they drive molecular and
    cellular innovations.
  </p>

  <div class="research-images">
    <img src="{{ '/assets/images/6962841056_04bd7b4b6f_c.jpg' | relative_url }}" alt="Research image">
    <img src="{{ '/assets/images/14831812109_248e71f584_c.jpg' | relative_url }}" alt="Research image">
    <img src="{{ '/assets/images/7294863010_93d13923bb_c.jpg' | relative_url }}" alt="Research image">
    <img src="{{ '/assets/images/4837265100_7ff68cd6f6_c.jpg' | relative_url }}" alt="Research image">
  </div>

  <div class="team-banner">
    <p><a href="{{ '/publications/' | relative_url }}">See Darras Lab publications →</a></p>
  </div>
</section>

<section class="section" id="people">
  <h2>People</h2>

  <div class="people-grid">
    <div class="person">
      <img class="avatar" src="{{ '/assets/images/miya-pan.png' | relative_url }}" alt="Miya Pan">
      <div class="name">Miya Pan</div>
      <div class="role">Principal Investigator</div>
      <div class="inst">IMB Mainz</div>
      <div><a href="mailto:miya.pan@imb.de">miya.pan@imb.de</a></div>
    </div>

    <div class="person">
      <img class="avatar" src="{{ '/assets/images/hugo-darras.png' | relative_url }}" alt="Hugo Darras">
      <div class="name">Hugo Darras</div>
      <div class="role">Principal Investigator</div>
      <div class="inst">JGU Mainz</div>
      <div><a href="mailto:hugo.darras@uni-mainz.de">hugo.darras@uni-mainz.de</a></div>
    </div>

    <div class="person">
      <img cl
