---
layout: default
title: Darras Lab
permalink: /
---

<style>
/* ---------- General layout ---------- */
.section { max-width: 1100px; margin: 0 auto; padding: 48px 16px; }
.lead { font-size: 1.05rem; line-height: 1.6; max-width: 75ch; }
.muted { opacity: 0.8; }

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
.person .lab,
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

/* ---------- Publications ---------- */
.pubs { margin-top: 14px; padding-left: 18px; }
.pubs li { margin: 8px 0; line-height: 1.5; }

/* Journal style (same blue as old publications page) */
.pub-journal {
  color: #1f4ed8;
  font-weight: 600;
  font-style: italic;
}
</style>

<section id="research" class="section">
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

<section id="people" class="section">
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

<section id="publications" class="section">
  <h2>Publications</h2>

  <ol class="pubs">
    <li><strong>Darras H.</strong>, Pan Q. 2024. Clonal ants reveal a potentially hidden meiotic feature. <span class="pub-journal">Trends in Genetics</span>, 40(11).</li>
    <li>Pan Q. (‡), <strong>Darras H.</strong> (‡), Keller L. 2024. LncRNA gene ANTSR coordinates complementary sex determination in the Argentine ant. <span class="pub-journal">Science Advances</span>, 10(22).</li>
    <li>Adolfi M.C., Depincé A., Wen M., Pan Q., Herpin A. 2023. Development of ovaries and sex change in fish: bringing potential into action. <span class="pub-journal">Sexual Development</span>, 17(2–3): 84–98.</li>
    <li>Wen M., Pan Q., Larson W., Eché C., Guiguen Y. 2023. Characterization of the sex determining region of channel catfish (<em>Ictalurus punctatus</em>) and development of a sex-genotyping test. <span class="pub-journal">Gene</span>, 850: 146933.</li>
    <li><strong>Darras H.</strong>, Berney C., Hasin S., Drescher J., Feldhaar H., Keller L. 2023. Obligate chimerism in male yellow crazy ants. <span class="pub-journal">Science</span>, 380(6640): 55–58.</li>
    <li>Pan Q., Herpin A., Guiguen Y. 2022. Inactivation of the anti-Müllerian hormone receptor type 2 gene in northern pike (<em>Esox lucius</em>) results in male-to-female sex reversal. <span class="pub-journal">Sexual Development</span>, 16(4): 289–294.</li>
    <li>Wen M., Pan Q., Jouanno E., et al. 2022. An ancient truncated duplication of the anti-Müllerian hormone receptor type 2 gene is a potential conserved master sex determinant in the Pangasiidae catfish family. <span class="pub-journal">Molecular Ecology Resources</span>, 22(6): 2411–2428.</li>
    <li>Tseng S.-P. (‡), <strong>Darras H.</strong> (‡), et al. 2022. Genetic analysis reveals the putative native range and widespread double-clonal reproduction in the invasive longhorn crazy ant. <span class="pub-journal">Molecular Ecology</span>, 32(5).</li>
    <li><strong>Darras H.</strong>, et al. 2022. Chromosome-level genome assembly and annotation of two lineages of the ant <em>Cataglyphis hispanica</em>. <span class="pub-journal">PCI Genomics</span>, 2(e40).</li>
    <li>Leniaud L. (‡), <strong>Darras H.</strong> (‡), Boulay R., Aron S. 2012. Social hybridogenesis in the clonal ant <em>Cataglyphis hispanica</em>. <span class="pub-journal">Current Biology</span>, 22(13): 1188–1193.</li>
  </ol>

  <p class="muted">‡ equal contributions</p>
</section>
