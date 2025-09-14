---
layout: default
title: Home
---

<!-- Hero / Banner -->
<div class="hero-banner">
  <img src="{{ '/assets/images/linepithema.png' | relative_url }}" alt="Linepithema illustration">
  <div class="hero-overlay">
    <h1>Haplodiploidy & Genetic Systems Labs</h1>
    <p>Investigating the evolution of sex determination and genetic systems</p>
  </div>
</div>

<!-- Intro / About -->
<section class="intro-card">
  <h2>Welcome</h2>
  <p>
    We are two closely collaborating research groups studying the evolution of sex determination and genetic systems in ants, bees, wasps, and other haplodiploid organisms. Our labs combine complementary expertise through collaboration, yet each maintains distinct research directions and identity.
  </p>
</section>

<!-- Research focus -->
<section class="research-cards">
  <h2>What we study</h2>
  <div class="cards-container">
    <div class="card">
      <h3>Haplodiploidy</h3>
      <p>Mechanisms & evolution of haplo-diploid sex determination systems.</p>
    </div>
    <div class="card">
      <h3>Genetic Systems</h3>
      <p>Comparative genomics of sex-determination pathways across insects.</p>
    </div>
    <div class="card">
      <h3>Colony evolution</h3>
      <p>How genetic systems influence social structure and reproduction.</p>
    </div>
  </div>
</section>

<!-- Team banner or link to People page -->
<section class="team-banner">
  <h2>Meet our team</h2>
  <p><a href="{{ '/people.html' | relative_url }}">See full team page →</a></p>
</section>

<!-- CSS -->
<style>
.hero-banner {
  position: relative;
  width: 100%;
  overflow: hidden;
  max-height: 500px;
  margin-bottom: 3rem;
}
.hero-banner img {
  width: 100%;
  height: auto;
  object-fit: cover;
  opacity: 0.8;
}
.hero-banner .hero-overlay {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  color: white;
  text-align: center;
  text-shadow: 0px 2px 8px rgba(0,0,0,0.6);
}
.hero-banner .hero-overlay h1 {
  font-size: 2.8rem;
  margin-bottom: 0.5rem;
}
.hero-banner .hero-overlay p {
  font-size: 1.3rem;
  font-weight: 300;
}

.intro-card {
  background: #f9f9f9;
  padding: 2rem;
  margin: 0 auto 3rem auto;
  max-width: 800px;
  border-radius: 8px;
}

.research-cards .cards-container {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
  gap: 2rem;
  margin: 2rem auto;
  max-width: 960px;
}
.research-cards .card {
  padding: 1.5rem;
  border: 1px solid #ddd;
  border-radius: 8px;
  transition: box-shadow 0.3s ease;
}
.research-cards .card:hover {
  box-shadow: 0px 6px 20px rgba(0,0,0,0.1);
  transform: translateY(-5px);
}

.team-banner {
  text-align: center;
  margin: 4rem 0;
}
.team-banner h2 {
  font-size: 1.8rem;
}
.team-banner p a {
  font-size: 1.1rem;
  color: #0077cc;
  text-decoration: none;
}
.team-banner p a:hover {
  text-decoration: underline;
}
</style>
