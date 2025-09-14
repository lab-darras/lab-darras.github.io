---
layout: default
title: People
---

## Meet the team

<style>
.group-leaders {
  display: flex;
  justify-content: center;
  gap: 150px;   /* more space between the pictures */
  margin-bottom: 60px;
  flex-wrap: wrap;
}


.people-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
  gap: 40px;
  justify-items: center;
  margin-top: 40px;
}

.person {
  text-align: center;
  max-width: 220px;
}

.person img {
  width: 160px;
  height: 160px;
  object-fit: cover;
  border-radius: 50%;
  box-shadow: 0px 4px 10px rgba(0,0,0,0.1);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.person img:hover {
  transform: scale(1.05);
  box-shadow: 0px 6px 15px rgba(0,0,0,0.2);
}

.person h3 {
  margin-top: 15px;
  margin-bottom: 5px;
  font-size: 1.1rem;
}

.person p {
  margin: 3px 0;
  color: #555;
  font-size: 0.9rem;
}

.person a {
  color: #0066cc;
  text-decoration: none;
  font-size: 0.9rem;
}

.person a:hover {
  text-decoration: underline;
}
</style>

<div class="group-leaders">
  <div class="person">
    <img src="{{ '/assets/images/miya-pan.png' | relative_url }}" alt="Miya Pan">
    <h3>Miya Pan</h3>
    <p>Principal Investigator</p>
    <p>Haplodiploidy Lab</p>
    <p>IMB Mainz</p>
    <p><a href="mailto:miya.pan@imb.de">miya.pan@imb.de</a></p>
  </div>
  <div class="person">
    <img src="{{ '/assets/images/hugo-darras.png' | relative_url }}" alt="Hugo Darras">
    <h3>Hugo Darras</h3>
        <p>Principal Investigator</p>

    <p>Genetic Systems Lab</p>
    <p>JGU Mainz</p>
    <p><a href="mailto:hugo.darras@uni-mainz.de">hugo.darras@uni-mainz.de</a></p>
  </div>
</div>

<div class="people-grid">
  <div class="person">
    <img src="{{ '/assets/images/chuanxin.png' | relative_url }}" alt="Chuanxin Yu">
    <h3>Chuanxin Yu</h3>
    <p>PhD Student</p>
        <p>Genetic Systems Lab</p>

    <p>JGU Mainz</p>
    <p><a href="mailto:chuanxin.yu@uni-mainz.de">chuanxin.yu@uni-mainz.de</a></p>
  </div>

  <div class="person">
    <img src="{{ '/assets/images/lena.png' | relative_url }}" alt="Lena Fröhlich">
    <h3>Lena Fröhlich</h3>
    <p>MSc Student</p>
          <p>Genetic Systems Lab</p>
        <p>JGU Mainz</p>
  </div>

  <div class="person">
    <img src="{{ '/assets/images/emilia.png' | relative_url }}" alt="Emilia María Romero Pineda">
    <h3>Emilia María Romero Pineda</h3>    
    <p>MSc Student</p>
          <p>Genetic Systems Lab</p>
        <p>JGU Mainz</p>
  </div>

</div>
