---
layout: default
title: Home
---

<div class="hero-banner">
  <img src="{{ '/assets/images/linepithema.png' | relative_url }}" alt="Linepithema illustration">
  <div class="hero-overlay">
    <h1>Investigating the evolution of sex determination and genetic systems</h1>
  </div>
</div>

# Welcome to the Haplodiploidy and Genetic Systems Labs!

We are two closely collaborating research groups studying the evolution of sex determination and genetic systems in ants, bees, wasps, and other haplodiploid organisms. Our labs combine complementary expertise through collaboration, yet each maintains distinct research directions and identity.

The **Haplodiploidy Lab** is based at the <a href="https://www.imb.de/" target="_blank">Institute of Molecular Biology</a> in Mainz, Germany. The **Genetic Systems Lab** is based at the <a href="https://iome.biology.uni-mainz.de/" target="_blank">Institute of Organismic and Molecular Evolution</a>, Johannes Gutenberg University Mainz, Germany.  

<div class="team-banner">
  <h2>Meet our team</h2>
  <p><a href="{{ '/people.html' | relative_url }}">See the full team →</a></p>
</div>

<style>
.hero-banner {
  position: relative;
  width: 100%;
  height: 55vh;        /* responsive height relative to screen */
  min-height: 300px;   /* don’t get too small */
  max-height: 600px;   /* don’t get too tall */
  overflow: hidden;
  margin-bottom: 2.5rem;
}

.hero-banner img {
  width: 100%;
  height: 100%;
  object-fit: cover;   /* cover container while cropping edges */
  opacity: 0.8;
}

.hero-overlay {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  text-align: center;
  color: white;
  text-shadow: 0px 2px 8px rgba(0,0,0,0.6);
  padding: 0 1rem; /* prevent text touching edges on small screens */
}

.hero-overlay h1 {
  font-size: 2.6rem;
  margin-bottom: 0.5rem;
  max-width: 700px;   /* keeps text tighter, ~2 lines */
  line-height: 1.3;   /* balanced spacing */
  text-align: center;
  margin-left: auto;
  margin-right: auto;
  word-break: normal;
  white-space: normal;
}


.hero-overlay .tagline {
  font-size: 1.3rem;
  font-weight: 300;
  margin: 0.5rem auto;
  max-width: 800px;
  text-align: center;   /* ensure horizontal centering */
  display: block;       /* keep full control */
}

.hero-overlay .location {
  font-size: 1.1rem;
  font-weight: 400;
  margin-top: 0.5rem;
  color: #f0f0f0;
}

/* Responsive adjustments */
@media (max-width: 768px) {
  .hero-overlay h1 {
    font-size: 2rem;
  }
  .hero-overlay .tagline {
    font-size: 1.1rem;
  }
  .hero-overlay .location {
    font-size: 1rem;
  }
}
  
/* Meet our team */
.team-banner {
  text-align: center;
  margin: 4rem 0;
}
.team-banner h2 {
  font-size: 1.8rem;
  margin-bottom: 0.5rem;
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
