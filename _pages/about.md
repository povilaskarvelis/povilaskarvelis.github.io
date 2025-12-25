---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  /* Base / Mobile Styles */
  .page__content {
    display: flex;
    flex-direction: column;
  }
  
  .image-gutter {
    order: 2; /* Appears after text on mobile */
    width: 100%;
    margin-top: 2em;
  }

  .main-about-text {
    order: 1; /* Appears before images on mobile */
  }

  .image-gutter div {
    margin-bottom: 20px;
  }

  .image-gutter img {
    width: 100%;
    height: auto;
    border: 1px solid #eee;
    padding: 4px;
    background: #fff;
  }

  /* Desktop Styles (Screens wider than 925px) */
  @media (min-width: 925px) {
    .page__content {
      display: block; /* Revert flex to allow floating */
    }

    .image-gutter {
      width: 200px;
      float: right;
      margin-right: -240px;
      margin-top: 0;
      clear: both;
    }
  }
</style>

<aside class="image-gutter">
  <div>
    <img src="{{ site.baseurl }}/images/pic1.jpg" alt="Image 1">
  </div>
  <div>
    <img src="{{ site.baseurl }}/images/pic3.jpg" alt="Image 3">
  </div>
  <div>
    <img src="{{ site.baseurl }}/images/pic4.jpg" alt="Image 4">
  </div>
</aside>

<div class="main-about-text" markdown="1">

I am a postdoctoral research fellow in the [Cognitive Network Modelling Lab](https://cognemo.com) at the [Krembil Centre for Neuroinformatics](https://www.camh.ca/en/science-and-research/institutes-and-centres/krembil-centre-for-neuroinformatics) at the Centre for Addiction and Mental Health, in Toronto, Canada.

I work at the intersection of computational neuroscience, psychometrics, and biostatistics, developing methods and tools to advance prediction models in precision psychiatry. My work spans multiple scales - from developing computational models and gamified cognitive assessments for specific disorders to addressing systemic problems in research practices.

At the disorder level, I have developed and experimentally tested Bayesian models for diverse conditions including psychosis, autism ([Karvelis et al., 2018](https://doi.org/10.7554/eLife.34115)), and suicidality ([Karvelis et al., 2022](https://doi.org/10.5334/cpsy.80)). Such models could provide novel computational markers for diagnosis and treatment - yet their promise depends on overcoming methodological barriers that affect the entire field.

At the field level, I have shown that novel computational assays often suffer from poor psychometric properties due to inadequate research designs, and provided a roadmap for developing reliable, valid and clinically effective instruments ([Karvelis et al., 2023](https://doi.org/10.1016/j.neubiorev.2023.105137)). I have further shown how poor measurement reliability problems extend to group differences designs and derived a set of equations to account for these effects ([Karvelis & Diaconescu, 2025](https://doi.org/10.3389/fpsyg.2025.1592658)). I have also detailed common methodological problems when applying machine learning for treatment response prediction ([Karvelis et al., 2022](https://doi.org/10.1162/netn_a_00233)). These issues create fundamental bottlenecks for both research and clinical translation, yet remain overlooked due to academic incentives that prioritize statistical significance over practical significance.

To address these broader systemic problems, I have developed an open-source simulation engine, [www.e2p-simulator.com](https://www.e2p-simulator.com), that helps researchers interpret findings and plan studies through the lens of real-world predictive utility.

More generally, I am interested in using computational tools to solve real-world problems while simultaneously exploring fundamental questions about the mind, intelligence, and knowledge.

</div>
