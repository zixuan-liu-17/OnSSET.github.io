---
theme: jekyll-theme-primer
layout: sub-page
title: OnSSET
permalink: /about/
---
<section class="bg-gray-light container-lg p-responsive py-4 py-md-6 my-lg-6 fade-in-center">
  <div class="text-center fade-in-center">
    <h2 class="alt-h3 mb-4">About OnSSET</h2>
    <div class="container-lg p-responsive py-4 py-md-6">
      <div class="col-md-12 animate-out mb-2">
        <p class="alt-lead text-gray text-justify-between col-md-15 mx-auto" style="text-align: justify; font-size: 0.875em;">
          <strong>OnSSET</strong> is a bottom-up optimization energy modelling tool that estimates, analyzes, 
          and visualizes the most cost-effective electrification strategy. It incorporates spatially explicit 
          characteristics related to energy — including population density and distribution, proximity to 
          transmission and road networks, nighttime lights, and local renewable energy potential.
          <br><br>
          OnSSET focuses on assessing and deploying conventional and renewable energy technologies to ensure access 
          to affordable, reliable, sustainable, and modern energy for all.
        </p>
      </div>

      <h2 class="aboutpage-subtitle text-left mb-3 mt-lg-6" id="what-does-it-do">What does it do?</h2>
      <div class="col-md-12 animate-out mb-2">
        <p class="alt-lead text-gray text-justify-between col-md-15 mx-auto" style="text-align: justify; font-size: 0.875em;">
          OnSSET is designed to complement existing energy planning models that do not consider geographical 
          characteristics related to energy. It provides invaluable support to policymakers and decision makers 
          seeking least-cost electrification strategies.
        </p>
      </div>

      <h2 class="aboutpage-subtitle text-left mb-3 mt-lg-6" id="scope-of-model">What is the scope of the model?</h2>
      <div class="col-md-12 animate-out mb-2">
        <p class="alt-lead text-gray text-justify-between col-md-15 mx-auto" style="text-align: justify; font-size: 0.875em;">
          Electrification planning is often dominated by proprietary analytical tools. OnSSET’s open-source and modular 
          structure allows users to build and modify the code according to their own data and requirements, enabling 
          rapid, cost-effective electrification plans. It reduces computational and data needs compared to many 
          existing resource-intensive planning tools.
        </p>
      </div>

      <h2 class="aboutpage-subtitle text-left mb-3 mt-lg-6" id="target-audience">Who is the target audience?</h2>
      <div class="col-md-12 animate-out mb-2">
        <p class="alt-lead text-gray text-justify-between col-md-15 mx-auto" style="text-align: justify; font-size: 0.875em;">
          The model is used extensively by academia, international organizations, and government institutions for 
          electrification planning, policy formulation, and research.
        </p>
      </div>

      <h2 class="aboutpage-subtitle text-left mb-3 mt-lg-6" id="outcomes">What outcomes can you obtain?</h2>
      <div class="col-md-12 animate-out mb-2">
        <p class="alt-lead text-gray text-justify-between col-md-15 mx-auto" style="text-align: justify; font-size: 0.875em;">
          OnSSET provides spatially explicit least-cost electrification options for a given geography, including 
          grid extensions, mini-grids, and standalone systems. It also estimates required investments and newly 
          installed power generation capacity.
        </p>
      </div>

      <h2 class="aboutpage-subtitle text-left mb-3 mt-lg-6" id="getting-started">How can you get started?</h2>
      <div class="col-md-12 animate-out mb-2">
        <p class="alt-lead text-gray text-justify-between col-md-15 mx-auto" style="text-align: justify; font-size: 0.875em;">
          The <a href="https://onsset.readthedocs.io/en/latest/index.html" target="_blank">OnSSET manual</a> is available on ReadTheDocs. 
          It provides installation guidance, functional descriptions, and a full walkthrough of geospatial electrification 
          analysis—from GIS preprocessing to running the model and visualizing results.
        </p>
      </div>

      <h2 class="aboutpage-subtitle text-left mb-3 mt-lg-6" id="contribute">How can you contribute?</h2>
      <div class="col-md-12 animate-out mb-2">
        <p class="alt-lead text-gray text-justify-between col-md-15 mx-auto" style="text-align: justify; font-size: 0.875em;">
          The OnSSET codebase is written in Python and hosted on GitHub, where anyone can download, use, and contribute 
          to its ongoing development. Contributions, feature requests, and collaboration are encouraged through the 
          <a href="https://github.com/onsset" target="_blank">OnSSET GitHub repository</a>.
        </p>
      </div>
    </div>
  </div>

  <!-- Icon Links -->
  <div class="icon-links-section">
    <div class="icon-links-wrapper">
      <!-- GitHub Repository -->
      <div class="icon-link-item">
        <a href="https://github.com/onsset" target="_blank">
          <img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" width="80" height="80" alt="GitHub" />
          <h3 class="aboutpage-subtitle text-primary">GitHub Repository</h3>
        </a>
      </div>

      <!-- Model Documentation -->
      <div class="icon-link-item">
        <a href="https://onsset.readthedocs.io/en/latest/index.html" target="_blank">
          <img src="/assets/img/Rtdicon.png" width="80" height="80" alt="ReadTheDocs icon" />
          <h3 class="aboutpage-subtitle text-primary">Model Documentation</h3>
        </a>
      </div>
    </div>
  </div>
</section>

<style>
.fade-in-center {
  opacity: 0;
  transform: translateY(20px);
  animation: fadeInUp 1s ease forwards;
}
@keyframes fadeInUp {
  to {
    opacity: 1;
    transform: translateY(0);
  }
}
.alt-h3 {
  font-size: 1.15rem;
}
@media (min-width: 768px) {
  .row.justify-content-center > .col-md-4 {
    margin-bottom: 2rem;
  }
}
</style>

