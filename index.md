---
layout: default
title: Darras Lab
permalink: /
---

<style>
/* --- One-page styling (research / people / publications) --- */
.section { max-width: 1100px; margin: 0 auto; padding: 48px 16px; }
.lead { font-size: 1.05rem; line-height: 1.6; max-width: 75ch; }
.muted { opacity: 0.8; }

.cards { display: grid; grid-template-columns: repeat(auto-fit, minmax(240px, 1fr)); gap: 14px; margin-top: 14px; }
.card { border: 1px solid rgba(0,0,0,0.12); border-radius: 12px; padding: 14px; background: #fff; }
.card h3 { margin: 0 0 8px 0; font-size: 1.05rem; }
.card p { margin: 0; line-height: 1.5; }

/* People: 5 per row with smaller circular avatars */
.people-grid {
  display: grid;
  grid-template-columns: repeat(5, minmax(0, 1fr));
  gap: 18px;
  margin-top: 18px;
  align-items: start;
}
@media (max-width: 1050px) {
  .people-grid { grid-template-columns: repeat(3, minmax(0, 1fr)); }
}
@media (max-width: 700px) {
  .people-grid { grid-template-columns: repeat(2, minmax(0, 1fr)); }
}
.person { text-align: center; }
.avatar {
  width: 110px;
  height: 110px;
  object-fit: cover;
  border-radius: 50%;
  box-shadow: 0px 4px 10px rgba(0,0,0,0.10);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}
.avatar:hover {
  transform: scale(1.05);
  box-shadow: 0px 6px 15px rgba(0,0,0,0.20);
}
.person .name { margin: 10px 0 3px 0; font-weight: 600; font-size: 1.02rem; }
.person .role, .person .lab, .person .inst {
  margin: 2px 0;
  font-size: 0.9rem;
  line-height: 1.25;
}
.person .role { font-weight: 600; }
.person .inst { opacity: 0.8; }
.person a { color: #0066cc; text-decoration: none; font-size: 0.9rem; }
.person a:hover { text-decoration: underline; }

/* Publications */
.pubs { margin-top: 14px; padding-left: 18px; }
.pubs li { margin: 8px 0; line-height: 1.5; }
</style>

<section id="research" class="section">
  <h1>Darras Lab</h1>
  <p class="lead">
    We study the genetics and evolution of insect societies, with a focus on sex determination, reproductive systems, and genome architecture in ants and other Hymenoptera.
  </p>

  <h2>Research projects</h2>
  <div class="cards">
    <div class="card">
      <h3>Sex determination across Hymenoptera</h3>
      <p>
        We investigate conserved sex-determining mechanisms and their evolutionary turnover, including cases with conserved function but no sequence homology.
      </p>
    </div>

    <div class="card">
      <h3>Genetic caste determination</h3>
      <p>
        We study systems in which queen and worker development is genetically constrained, including hybrid worker production and lineage-specific reproduction.
      </p>
    </div>

    <div class="card">
      <h3>Genome evolution in social insects</h3>
      <p>
        We combine long-read genome assemblies, population genomics, and functional analyses to study supergenes, structural variation, and regulatory evolution.
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
      <div class="lab">Haplodiploidy Lab</div>
      <div class="inst">IMB Mainz</div>
      <div><a href="mailto:miya.pan@imb.de">miya.pan@imb.de</a></div>
    </div>

    <div class="person">
      <img class="avatar" src="{{ '/assets/images/hugo-darras.png' | relative_url }}" alt="Hugo Darras">
      <div class="name">Hugo Darras</div>
      <div class="role">Principal Investigator</div>
      <div class="lab">Genetic Systems Lab</div>
      <div class="inst">JGU Mainz</div>
      <div><a href="mailto:hugo.darras@uni-mainz.de">hugo.darras@uni-mainz.de</a></div>
    </div>

    <div class="person">
      <img class="avatar" src="{{ '/assets/images/chuanxin.png' | relative_url }}" alt="Chuanxin Yu">
      <div class="name">Chuanxin Yu</div>
      <div class="role">PhD Student</div>
      <div class="lab">Genetic Systems Lab</div>
      <div class="inst">JGU Mainz</div>
      <div><a href="mailto:chuanxin.yu@uni-mainz.de">chuanxin.yu@uni-mainz.de</a></div>
    </div>

    <div class="person">
      <img class="avatar" src="{{ '/assets/images/lena.png' | relative_url }}" alt="Lena Fröhlich">
      <div class="name">Lena Fröhlich</div>
      <div class="role">MSc Student</div>
      <div class="lab">Genetic Systems Lab</div>
      <div class="inst">JGU Mainz</div>
    </div>

    <div class="person">
      <img class="avatar" src="{{ '/assets/images/emilia.png' | relative_url }}" alt="Emilia María Romero Pineda">
      <div class="name">Emilia María Romero Pineda</div>
      <div class="role">MSc Student</div>
      <div class="lab">Genetic Systems Lab</div>
      <div class="inst">JGU Mainz</div>
    </div>
  </div>
</section>

<section id="publications" class="section">
  <h2>Publications</h2>

  <ol class="pubs">
    <li><strong>Darras H.</strong>, Pan Q. 2024. Clonal ants reveal a potentially hidden meiotic feature. <strong><em>Trends in Genetics</em></strong>, 40(11).</li>
    <li>Pan Q. (‡), <strong>Darras H.</strong> (‡), Keller L. 2024. LncRNA gene ANTSR coordinates complementary sex determination in the Argentine ant. <strong><em>Science Advances</em></strong>, 10(22).</li>
    <li>Adolfi M.C., Depincé A., Wen M., Pan Q., Herpin A. 2023. Development of ovaries and sex change in fish: bringing potential into action. <strong><em>Sexual Development</em></strong>, 17(2–3): 84–98.</li>
    <li>Wen M., Pan Q., Larson W., Eché C., Guiguen Y. 2023. Characterization of the sex determining region of channel catfish (<em>Ictalurus punctatus</em>) and development of a sex-genotyping test. <strong><em>Gene</em></strong>, 850: 146933.</li>
    <li><strong>Darras H.</strong>, Berney C., Hasin S., Drescher J., Feldhaar H., Keller L. 2023. Obligate chimerism in male yellow crazy ants. <strong><em>Science</em></strong>, 380(6640): 55–58.</li>
    <li>Pan Q., Herpin A., Guiguen Y. 2022. Inactivation of the anti-Müllerian hormone receptor type 2 (amhrII) gene in northern pike (<em>Esox lucius</em>) results in male-to-female sex reversal. <strong><em>Sexual Development</em></strong>, 16(4): 289–294.</li>
    <li>Wen M., Pan Q., Jouanno E., et al. 2022. An ancient truncated duplication of the anti-Müllerian hormone receptor type 2 gene is a potential conserved master sex determinant in the Pangasiidae catfish family. <strong><em>Molecular Ecology Resources</em></strong>, 22(6): 2411–2428.</li>
    <li>Tseng S.-P. (‡), <strong>Darras H.</strong> (‡), Hsu P.-W., Yoshimura T., Lee C.-Y., Wetterer J.K., Keller L., Yang C.C.S. 2022. Genetic analysis reveals the putative native range and widespread double-clonal reproduction in the invasive longhorn crazy ant. <strong><em>Molecular Ecology</em></strong>, 32(5).</li>
    <li><strong>Darras H.</strong>, de Souza Araujo N., Baudry L., Guiglielmoni N., Lorite P., Marbouty M., Rodriguez F., Arkhipova I., Koszul R., Flot J.F., Aron S. 2022. Chromosome-level genome assembly and annotation of two lineages of the ant <em>Cataglyphis hispanica</em>. <strong><em>PCI Genomics</em></strong>, 2(e40).</li>
    <li>Imarazene B., Du K., Beille S., Jouanno E., Feron R., Pan Q., et al. 2021. A supernumerary B-sex chromosome drives male sex determination in the Pachón cavefish, <em>Astyanax mexicanus</em>. <strong><em>Current Biology</em></strong>, 31(21): 4800–4809.e9.</li>
    <li>Thompson A., Hawkins M., Parey E., Wcisel D., Ota T., Kawasaki K., Funk E., Losilla M., Fitch O., Pan Q., et al. 2021. The bowfin genome illuminates the developmental evolution of ray-finned fishes. <strong><em>Nature Genetics</em></strong>, 53(9): 1373–1384.</li>
    <li>Pan Q., Kay T., Depincé A., Adolfi M., Schartl M., Guiguen Y., Herpin A. 2021. Evolution of master sex determiners: TGF-β signalling pathways at regulatory crossroads. <strong><em>Philosophical Transactions of the Royal Society B</em></strong>, 376(1832): 20200091.</li>
    <li>Pan Q., Feron R., Jouanno E., <strong>Darras H.</strong>, Herpin A., Koop B., Rondeau E., Goetz F.W., Larson W.A., Bernatchez L., et al. 2021. The rise and fall of the ancient northern pike master sex-determining gene. <strong><em>eLife</em></strong>, 10: e62858.</li>
    <li>Feron R., Pan Q., Wen M., Imarazene B., et al. 2021. RADSex: a computational workflow to study sex determination using Restriction Site–Associated DNA sequencing data. <strong><em>Molecular Ecology Resources</em></strong>, 21(5): 1715–1731.</li>
    <li>Bujan J., Charavel E., Bates O.K., Gippet J.M.W., <strong>Darras H.</strong>, Lebas C., Bertelsmeier C. 2021. Increased acclimation ability accompanies a thermal niche shift of a recent invasion. <strong><em>Journal of Animal Ecology</em></strong>, 90(2): 483–491.</li>
    <li>Kuhn A. (‡), <strong>Darras H.</strong> (‡), Paknia O., Aron S. 2020. Repeated evolution of queen parthenogenesis and social hybridogenesis in <em>Cataglyphis</em> desert ants. <strong><em>Molecular Ecology</em></strong>, 29(3): 549–564.</li>
    <li>Wen M., Feron R., Pan Q., Guiguen Y., Jouanno E., et al. 2020. Sex chromosome and sex locus characterization in goldfish, <em>Carassius auratus</em>. <strong><em>BMC Genomics</em></strong>, 21(1): 552.</li>
    <li>Pan Q., Feron R., Yano A., Guyomard R., Jouanno E., et al. 2019. Identification of the master sex-determining gene in northern pike (<em>Esox lucius</em>) reveals restricted sex chromosome differentiation. <strong><em>PLOS Genetics</em></strong>, 15(8): e1008013.</li>
    <li>Tseng S.-P., <strong>Darras H.</strong>, Lee C.-Y., Yoshimura T., Keller L., Yang C.C.S. 2019. Isolation and characterization of novel microsatellite markers for <em>Paratrechina longicornis</em>. <strong><em>European Journal of Entomology</em></strong>, 116: 253–257.</li>
    <li><strong>Darras H.</strong>, Kuhn A., Aron S. 2019. Evolution of hybridogenetic lineages in <em>Cataglyphis</em> ants. <strong><em>Molecular Ecology</em></strong>, 28(12): 3073–3088.</li>
    <li>Kuhn A. (‡), <strong>Darras H.</strong> (‡), Aron S. 2018. Phenotypic plasticity in an ant with strong caste-genotype association. <strong><em>Biology Letters</em></strong>, 14(1): 20170705.</li>
    <li>Kuhn A., Bauman D., <strong>Darras H.</strong>, Aron S. 2017. Sex-biased dispersal creates spatial genetic structure in a parthenogenetic ant with a dependent-lineage reproductive system. <strong><em>Heredity</em></strong>, 119(4): 207–213.</li>
    <li>Norman V. (‡), <strong>Darras H.</strong> (‡), Tranter C., Aron S., Hughes W.O.H. 2016. Cryptic lineages hybridize for worker production in the harvester ant <em>Messor barbarus</em>. <strong><em>Biology Letters</em></strong>, 12(11): 20160542.</li>
    <li><strong>Darras H.</strong>, Aron S. 2015. Introgression of mitochondrial DNA among lineages in a hybridogenetic ant. <strong><em>Biology Letters</em></strong>, 11(2): 20140971.</li>
    <li><strong>Darras H.</strong>, Kuhn A., Aron S. 2014. Genetic determination of female castes in a hybridogenetic desert ant. <strong><em>Journal of Evolutionary Biology</em></strong>, 27(10): 2265–2271.</li>
    <li><strong>Darras H.</strong>, Leniaud L., Aron S. 2013. Large-scale distribution of hybridogenetic lineages in a Spanish desert ant. <strong><em>Proceedings of the Royal Society B</em></strong>, 281(1774): 20132396.</li>
    <li>Eyer P.A., Leniaud L., <strong>Darras H.</strong>, Aron S. 2013. Hybridogenesis through thelytokous parthenogenesis in two <em>Cataglyphis</em> desert ants. <strong><em>Molecular Ecology</em></strong>, 22(4): 947–955.</li>
    <li>Leniaud L. (‡), <strong>Darras H.</strong> (‡), Boulay R., Aron S. 2012. Social hybridogenesis in the clonal ant <em>Cataglyphis hispanica</em>. <strong><em>Current Biology</em></strong>, 22(13): 1188–1193.</li>
  </ol>

  <p class="muted">‡ equal contributions</p>
</section>
