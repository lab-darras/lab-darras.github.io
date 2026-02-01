---
layout: default
title: Darras Lab - Evolution of genomic conflicts
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
  grid-template-columns:repeat(4, minmax(0,1fr));
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
  
<style>
  .lab-text a {
    color: #2f4a6d;
    text-decoration: none;
  }

  .lab-text a:hover {
    text-decoration: underline;
  }
</style>

<div class="lab-text">

  <p>Our lab studies how genes that increase their chance of being inherited during reproduction can disrupt other biological functions, alter development, and shape species traits and genome evolution.</p>

  <p>A central challenge in evolutionary biology and medicine is to understand how such genes emerge and persist in populations. A familiar example of biological conflict is the human pelvis, whose shape reflects a long-standing evolutionary compromise between selection for efficient childbirth in females and selection for effective upright locomotion in males. In this case, the same genetic variants influence pelvic development in both sexes, yet they are subject to different selective pressures. More generally, conflicts arise when genes increase their own transmission during reproduction, even when this reduces organismal performance or interferes with normal development. Such genes are often referred to as “selfish genes”. Manifestations of genetic conflict occur at multiple biological levels, from genes and cells to individuals. Despite many documented examples, we still know little about how these genes are distributed across genomes or how they shape genome architecture, partly because their effects are usually transient and difficult to detect.</p>

  <p>Our research focuses on early insect development, from gamete formation to the earliest stages of cell differentiation. We study social insects in which individuals with nearly identical genomes can develop into either reproductive queens or non-reproductive workers. In these species, selfish genetic variants can bias development toward the reproductive role, generating conflicts between alternative developmental trajectories. These conflicts have repeatedly driven the emergence of unusual genetic systems in which queen and worker development is no longer flexible but genetically predetermined. In some cases, this transition is associated with striking cellular mechanisms, including clonal inheritance of the maternal genome. These systems provide rare natural experiments to uncover how genetic conflicts reshape development and drive the evolution of novel molecular and cellular mechanisms.</p>

  <p>We combine comparative genomics with functional experiments to identify genetic conflicts, characterize the molecular pathways involved, and reconstruct their evolutionary origins in ants.</p>

  <p>Our lab is based at the <a href="https://evolution.zju.edu.cn/en/index.html">Centre for Evolutionary and Organismal Biology</a> at Zhejiang University. We collaborate extensively with the Pan Lab (<a href="https://www.phd.tuebingen.mpg.de/36499/Qiaowei-_Miya_-Pan">Insect sex determination and development</a>) at the Max Planck Institute for Biology, Tübingen, through shared resources and projects.</p>

</div>


<div style="height:40px;"></div>

  <div class="people-grid">
      <div class="person">
      <img class="avatar" src="{{ '/assets/images/hugo-darras.png' | relative_url }}" alt="Hugo Darras">
      <div class="name">Hugo Darras</div>
      <div class="role">Principal Investigator</div>
      <div><a href="mailto:hdarras@zju.edu.cn">hdarras@zju.edu.cn</a></div>
    </div>
    
    <div class="person">
      <img class="avatar" src="{{ '/assets/images/miya-pan.png' | relative_url }}" alt="Miya Pan">
      <div class="name">Qiaowei (Miya) Pan</div>
      <div class="role">Co-investigator</div>
      <div><a href="mailto:qiaowei.pan@tuebingen.mpg.de">qiaowei.pan@tuebingen.mpg.de</a></div>
    </div>
    
    <div class="person">
      <img class="avatar" src="{{ '/assets/images/chuanxin.png' | relative_url }}" alt="Chuanxin Yu">
      <div class="name">Chuanxin Yu</div>
      <div class="role">PhD Student</div>
      <div><a href="mailto:chuyu@uni-mainz.de">chuyu@uni-mainz.de</a></div>
    </div>

    <div class="person">
      <img class="avatar" src="{{ '/assets/images/lena.png' | relative_url }}" alt="Lena Fröhlich">
      <div class="name">Lena Fröhlich</div>
      <div class="role">MSc Student</div>
    </div>

  </div>

  <div class="research-images" style="display:flex; gap:2%; justify-content:center; margin-top:70px;">
  <img src="{{ '/assets/images/6962841056_04bd7b4b6f_c.jpg' | relative_url }}" alt="Research image" style="width:21%; height:auto; object-fit:cover;">
  <img src="{{ '/assets/images/14831812109_248e71f584_c.jpg' | relative_url }}" alt="Research image" style="width:21%; height:auto; object-fit:cover;">
  <img src="{{ '/assets/images/7294863010_93d13923bb_c.jpg' | relative_url }}" alt="Research image" style="width:21%; height:auto; object-fit:cover;">
  <img src="{{ '/assets/images/4837265100_7ff68cd6f6_c.jpg' | relative_url }}" alt="Research image" style="width:21%; height:auto; object-fit:cover;">
</div>

</section>
