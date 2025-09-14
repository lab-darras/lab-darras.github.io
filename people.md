---
layout: default
title: People
---

## People

<style>
.people-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
  gap: 30px;
  justify-items: center;
  margin-top: 40px;
}

.person {
  text-align: center;
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
  margin: 0;
  color: #555;
  font-size: 0.9rem;
}
</style>

## Group Leaders

<div class="people-grid">
  <div class="person">
    <img src="{{ '/assets/images/miya-pan.png' | relative_url }}" alt="Miya Pan">
    <h3>Qiaowei "Miya" Pan</h3>
    <p>Principal Investigator, Haplodiploidy Lab</p>
  </div>

  <div class="person">
    <img src="{{ '/assets/images/hugo-darras.png' | relative_url }}" alt="Hugo Darras">
    <h3>Hugo Darras</h3>
    <p>Principal Investigator, Genetic systems Lab</p>
  </div>
</div>

<div class="people-grid">
  <div class="person">
    <img src="{{ '/assets/images/chuanxin.png' | relative_url }}" alt="Student 1">
    <h3>Chuanxin Yu</h3>
    <p>PhD Student</p>
  </div>

  <div class="person">
    <img src="{{ '/assets/images/lena.png' | relative_url }}" alt="Student 2">
    <h3>Lena Fröhlich</h3>
    <p>MSc Student</p>
  </div>

  <div class="person">
    <img src="{{ '/assets/images/emilia.png' | relative_url }}" alt="Student 3">
    <h3>Emilia Maria Romero Pineda </h3>
    <p>MSc Student</p>
  </div>
