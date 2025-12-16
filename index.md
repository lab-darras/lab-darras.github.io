---
layout: default
title: Darras Lab
permalink: /
---

<style>
/* ---------- General layout ---------- */
.section { padding: 48px 0; }
.lead { font-size: 1.05rem; line-height: 1.6; max-width: 75ch; }

/* ---------- Research cards ---------- */
.cards {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
  gap: 14px;
  margin-top: 14px;
}
.card {
  border: 1px solid rgba(0,0,0,0.12);
  border-radius: 12px;
  padding: 14px;
  background: #fff;
}
.card h3 { margin: 0 0 8px 0; font-size: 1.05rem; }
.card p { margin: 0; line-height: 1.5; }

/* ---------- People (5 per row) ---------- */
.people-grid {
  display: grid;
  grid-template-columns: repeat(5, minmax(0, 1fr));
  gap: 18px;
  margin-top: 20px;
}
@media (max-width: 1050px) {
  .people-grid { grid-template-columns: repeat(3, 1fr); }
}
@media (max-width: 700px) {
  .people-grid { grid-template-columns: repeat(2, 1fr); }
}

.person { text-align: center; }
.avatar {
  width: 110px;
  height: 110px;
  object-fit: cover;
  border-radius: 50%;
  box-shadow: 0 4px 10px rgba(0,0,0,0.10);
}
.person .name {
  margin-top: 10px;
  font-weight: 600;
  font-size: 1.02rem;
}
.person .role,
.person .inst {
  font-size: 0.9rem;
  line-height: 1.25;
}
.person .role { font-weight: 600; }
.person .inst { opacity: 0.8; }
.person a {
  font-size: 0.9rem;
  color: #0066cc;
  text-decoration: none;
}
.person a:hover { text-decoration: underline; }
</style>

<section class="section" id="research">
  <h1>Darras Lab</h1>
  <p class="lead">
    We study the genetics and evolution of insect societies, with a focus on sex determination,
    reproductive systems, and genome architecture in ants and other Hymenoptera.
  </p>

  <h2>Research projects</h2>
  <div class="cards">
    <div class="card">
      <h3>Sex determination across Hymenoptera</h3>
      <p>
        We investigate conserved sex-determining mechanisms and their evolutionary turnover,
        including cases with conserved function but no sequence homology.
      </p>
    </div>

    <div class="card">
      <h3>Genetic caste determination</h3>
      <p>
        We study systems in which queen and worker development is genetically constrained,
        including hybrid worker production and lineage-specific reproduction.
      </p>
    </div>

    <div class="card">
      <h3>Genome evolution in social insects</h3>
      <p>
        We combine long-read genome assemblies, population genomics, and functional analyses
        to study supergenes, structural variation, and regulatory evolution.
      </p>
    </div>
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
      <img class="avatar" src="{{ '/assets/images/chuanxin.png' | relative_url }}" alt="Chuanxin Yu">
      <div class="name">Chuanxin Yu</div>
      <div class="role">PhD Student</div>
      <div class="inst">JGU Mainz</div>
      <div><a href="mailto:chuanxin.yu@uni-mainz.de">chuanxin.yu@uni-mainz.de</a></div>
    </div>

    <div class="person">
      <img class="avatar" src="{{ '/assets/images/lena.png' | relative_url }}" alt="Lena Fröhlich">
      <div class="name">Lena Fröhlich</div>
      <div class="role">MSc Student</div>
      <div class="inst">JGU Mainz</div>
    </div>

    <div class="person">
      <img class="avatar" src="{{ '/assets/images/emilia.png' | relative_url }}" alt="Emilia María Romero Pineda">
      <div class="name">Emilia María Romero Pineda</div>
      <div class="role">MSc Student</div>
      <div class="inst">JGU Mainz</div>
    </div>
  </div>
</section>
