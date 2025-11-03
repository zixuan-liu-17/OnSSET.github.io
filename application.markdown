---
theme: jekyll-theme-primer
layout: sub-page
title: OnSSET
permalink: /applications/
---
<section class="bg-gray-light container-lg p-responsive py-4 py-md-6 my-lg-6 fade-in-center"> 
  <div class="text-center fade-in-center">
    <h2 class="alt-h2 mb-4">OnSSET Applications</h2>
  </div>

  <div class="applications-content text-left">
    <p class="lead mb-4">
      <em>“OnSSET is a fundamental building block for a wide range of applications across government, industry, and academia. Several examples include:”</em>
    </p>

    <div class="applications-grid">
      <!-- Governments -->
      <div class="application-category">
        <h3 class="category-title">Governments</h3>
        <p>
          OnSSET has supported electrification efforts in many countries around the globe including Afghanistan, Nigeria, Ethiopia, Kenya, India, Tanzania, Madagascar and Benin as part of joint collaborations with the World Bank, the United Nations, and SNV.
        </p>
        <ul class="application-list">
          <li><a href="https://energypedia.info/wiki/File:A_GIS_approach_to_electrification_planning_in_Afghanistan.pdf" target="_blank">Afghanistan: A GIS approach to electrification planning in Afghanistan</a></li>
          <li><a href="https://www.energy.kth.se/energy-systems/completed-projects/least-cost-electrification-pathways-for-benin-1.1199071" target="_blank">Benin: Least-cost electrification Pathways for Benin</a></li>
        </ul>  
      </div>

      <!-- Industry and Think Tanks -->
      <div class="application-category">
        <h3 class="category-title">Industry and Think Tanks</h3>
        <ul class="application-list">
          <li><a href="https://electrifynow.energydata.info/" target="_blank">Global Electrification Platform</a> – An open-access, interactive online platform providing electrification investment scenarios for multiple countries. The GEP informs key global reports such as <em>Tracking SDG7</em> and <em>Mini-grids for Half a Billion People</em>.</li>

          <li>IEA’s <em>World Energy Outlooks</em> – OnSSET analysis has been featured in several editions (2014, 2015, 2017, 2019, and 2022).</li>

          <li><a href="https://www.wri.org/research/application-gis-sub-national-energy-planning-kenya-integrating-primary-data-least-cost" target="_blank">World Resources Institute (WRI) Case Study</a> – Application of GIS in Sub-National Energy Planning in Kenya (Narok County), integrating primary data into least-cost electrification modelling using OnSSET.</li>

          <li><a href="https://accessplanning.irena.org/" target="_blank">IRENA West Africa Electrification Platform</a> – An interactive platform providing investment scenario insights for West African countries.</li>
        </ul>
      </div>

      <!-- Academia -->
      <div class="application-category">
        <h3 class="category-title">Academia</h3>
        <p>OnSSET has been widely applied in academic research to advance understanding of electrification planning, least-cost pathways, and the integration of social, environmental, and financial factors. Selected publications include:</p>
        <ul class="application-list">
          <li><a href="https://doi.org/10.3390/en16186489" target="_blank">Comparison of Least-Cost Pathways towards Universal Electricity Access in Somalia</a>, Energies, 2023.</li>
          <li><a href="https://doi.org/10.1007/s43937-023-00014-4" target="_blank">Exploring Long-Term Electrification Pathway Dynamics: Ethiopia</a>, Discover Energy, 2023.</li>
          <li><a href="https://doi.org/10.1038/s41467-023-40612-3" target="_blank">The Cost of Electrifying All Households in 40 Sub-Saharan African Countries by 2030</a>, Nature Communications, 2023.</li>
          <li><a href="https://doi.org/10.1016/j.esr.2022.101021" target="_blank">Achieving Universal Electricity Access in Nigeria</a>, Energy Strategy Reviews, 2023.</li>
          <li><a href="https://doi.org/10.1016/j.apenergy.2020.114749" target="_blank">Planning with Justice: Tanzania</a>, Applied Energy, 2020.</li>
          <li><a href="https://doi.org/10.3390/en12071395" target="_blank">The Role of Open Access Data in Geospatial Electrification Planning – Malawi</a>, Energies, 2019.</li>
          <li><a href="https://doi.org/10.1088/1748-9326/aa7b29" target="_blank">Lighting the World: The First Application of OnSSET in Sub-Saharan Africa</a>, Environmental Research Letters, 2017.</li>
          <li><a href="https://doi.org/10.1016/j.esd.2015.09.007" target="_blank">A GIS-Based Approach for Electrification Planning – Nigeria</a>, Energy for Sustainable Development, 2015.</li>
        </ul>
      </div>
    </div>
  </div>
</section>

 <section class="container-lg p-responsive py-4 py-md-6 my-lg-6">
  <div class="text-center mb-5">
    <h2 class="alt-h2">Specialist Applications</h2>
  </div>

  <div class="slider-wrapper my-5">
    <div class="arrow arrow-left" onclick="slideTextPrev()">‹</div>

    <div class="slider-container">
      <div class="slider" id="textSlider">

        <div class="slide-card">
          <h3>Kenya Electrification Pathways</h3>
          <p>
            <a href="https://doi.org/10.1088/1748-9326/aa7e18" target="_blank">
              Electrification pathways for Kenya – linking spatial electrification analysis and medium to long-term energy planning
            </a>
          </p>
        </div>

        <div class="slide-card">
          <h3>Planning with Justice – Tanzania</h3>
          <p>
            <a href="https://doi.org/10.1016/j.apenergy.2020.114749" target="_blank">
              Using spatial modelling to incorporate justice in electricity pricing – The case of Tanzania
            </a>
          </p>
        </div>

        <div class="slide-card">
          <h3>Urban–Rural Electrification Data</h3>
          <p>
            <a href="https://doi.org/10.1038/s41597-021-00897-9" target="_blank">
              Population cluster data to assess the urban–rural split and electrification in Sub-Saharan Africa
            </a>
          </p>
        </div>

      </div>
    </div>

    <div class="arrow arrow-right" onclick="slideTextNext()">›</div>
  </div>

  <div class="slider-dots text-center mt-3" id="sliderDots"></div>
</section>

<section class="container-lg p-responsive py-4 py-md-6 my-lg-6">
  <div class="recommended-reading">
    <h2 class="alt-h2 text-center mb-4">Recommended Reading</h2>
    <p class="text-center mb-5">For a broader analysis of applications and advancements in OnSSET, see the following peer-reviewed publications:</p>

    <div class="publications-list">
      {% for publication in site.data.publications %}
      <div class="publication-item mb-4 p-4 border border-gray-200 rounded">
        <h4 class="publication-title mb-2">
          <a href="{{ publication.url }}" target="_blank" class="text-decoration-none">
            {{ publication.title }}
          </a>
        </h4>
        <p class="publication-authors text-muted mb-2">
          {{ publication.authors }} ({{ publication.year }})
        </p>
        <p class="publication-journal mb-2">
          <em>{{ publication.journal }}</em>
        </p>
        <p class="publication-abstract text-justify">
          {{ publication.abstract }}
        </p>
      </div>
      {% endfor %}
    </div>

  </div>
  
</section>

<style>
/* Enhanced Applications Page Styling */
.applications-content {
  max-width: 1200px;
  margin: 0 auto;
}

.applications-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2rem;
  margin-top: 2rem;
}

.application-category {
  background: white;
  padding: 2rem;
  border-radius: 12px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
  transition: all 0.3s ease;
}

.application-category:hover {
  transform: translateY(-4px);
  box-shadow: 0 8px 25px rgba(0, 0, 0, 0.15);
}

.category-title {
  color: #0366d6;
  font-size: 1.3rem;
  font-weight: 600;
  margin-bottom: 1rem;
  padding-bottom: 0.5rem;
  border-bottom: 2px solid #e1e4e8;
}

.application-list {
  list-style: none;
  padding: 0;
  margin: 0;
}

.application-list li {
  margin-bottom: 0.8rem;
  padding-left: 1.5rem;
  position: relative;
}

.application-list li::before {
  content: "→";
  position: absolute;
  left: 0;
  color: #0366d6;
  font-weight: bold;
}

.application-list a {
  color: #24292e;
  text-decoration: none;
  transition: color 0.3s ease;
  line-height: 1.5;
}

.application-list a:hover {
  color: #0366d6;
  text-decoration: underline;
}

/* Enhanced Slider Styling */
.slider-wrapper {
  position: relative;
  max-width: 800px;
  margin: 0 auto;
  display: flex;
  align-items: center;
}

.slider-container {
  overflow: hidden;
  width: 100%;
  border-radius: 12px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
}

.slider {
  display: flex;
  transition: transform 0.6s ease-in-out;
}

.slide-card {
  min-width: 100%;
  padding: 2.5rem;
  background: linear-gradient(135deg, #f8f9fa 0%, #e9ecef 100%);
  border-left: 5px solid #0366d6;
  text-align: center;
  transition: all 0.3s ease;
}

.slide-card:hover {
  background: linear-gradient(135deg, #ffffff 0%, #f8f9fa 100%);
  transform: scale(1.02);
}

.slide-card h3 {
  margin-bottom: 1rem;
  color: #24292e;
  font-size: 1.5rem;
  font-weight: 600;
}

.slide-card a {
  color: #0366d6;
  text-decoration: none;
  font-weight: 500;
  font-size: 1.1rem;
  transition: all 0.3s ease;
}

.slide-card a:hover {
  color: #0056b3;
  text-decoration: underline;
}

.arrow {
  font-size: 2.5rem;
  cursor: pointer;
  user-select: none;
  padding: 0.5rem 1rem;
  color: #0366d6;
  background: rgba(255, 255, 255, 0.9);
  border-radius: 8px;
  transition: all 0.3s ease;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
}

.arrow:hover {
  background: white;
  transform: scale(1.1);
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
}

.arrow-left {
  position: absolute;
  left: -50px;
}

.arrow-right {
  position: absolute;
  right: -50px;
}

.slider-dots {
  display: flex;
  justify-content: center;
  gap: 12px;
  margin-top: 1.5rem;
}

.slider-dots .dot {
  width: 12px;
  height: 12px;
  background-color: #d1d5da;
  border-radius: 50%;
  cursor: pointer;
  transition: all 0.3s ease;
}

.slider-dots .dot:hover {
  background-color: #0366d6;
  transform: scale(1.2);
}

.slider-dots .dot.active {
  background-color: #0366d6;
  transform: scale(1.2);
}

/* Enhanced Publications Styling */
.recommended-reading {
  max-width: 1000px;
  margin: 0 auto;
}

.publications-list {
  display: flex;
  flex-direction: column;
  gap: 2rem;
}

.publication-item {
  background: white;
  padding: 2rem;
  border-radius: 12px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
  transition: all 0.3s ease;
  border-left: 4px solid #0366d6;
}

.publication-item:hover {
  transform: translateY(-2px);
  box-shadow: 0 8px 25px rgba(0, 0, 0, 0.15);
}

.publication-header {
  margin-bottom: 1rem;
}

.publication-title {
  font-size: 1.2rem;
  font-weight: 600;
  color: #24292e;
  margin-bottom: 0.5rem;
  line-height: 1.4;
}

.publication-authors {
  font-weight: 500;
  color: #586069;
  margin-bottom: 0.3rem;
}

.publication-journal {
  font-style: italic;
  color: #586069;
  margin-bottom: 0.5rem;
}

.publication-link {
  color: #0366d6;
  text-decoration: none;
  font-size: 0.9rem;
  word-break: break-all;
}

.publication-link:hover {
  text-decoration: underline;
}

.publication-abstract {
  color: #586069;
  line-height: 1.6;
  font-size: 0.95rem;
  text-align: justify;
}

/* Responsive Design */
@media (max-width: 768px) {
  .applications-grid {
    grid-template-columns: 1fr;
    gap: 1.5rem;
  }
  
  .application-category {
    padding: 1.5rem;
  }
  
  .arrow-left {
    left: -30px;
  }
  
  .arrow-right {
    right: -30px;
  }
  
  .slide-card {
    padding: 2rem 1.5rem;
  }
  
  .publication-item {
    padding: 1.5rem;
  }
}

@media (max-width: 480px) {
  .arrow {
    font-size: 2rem;
    padding: 0.3rem 0.8rem;
  }
  
  .arrow-left {
    left: -25px;
  }
  
  .arrow-right {
    right: -25px;
  }
}

/* Enhanced fade-in animations */
.fade-in-center {
  opacity: 0;
  transform: translateY(30px);
  animation: fadeInUp 1.2s ease-out forwards;
}

@keyframes fadeInUp {
  to {
    opacity: 1;
    transform: translateY(0);
  }
}
</style>

<script>
// Enhanced Slider Functionality
let slideIndex = 0;
const textSlider = document.getElementById("textSlider");
const textSlides = textSlider.children.length;
const dotsContainer = document.getElementById("sliderDots");

function updateSlider() {
  textSlider.style.transform = `translateX(-${slideIndex * 100}%)`;
  updateDots();
}

function slideTextNext() {
  slideIndex = (slideIndex + 1) % textSlides;
  updateSlider();
}

function slideTextPrev() {
  slideIndex = (slideIndex - 1 + textSlides) % textSlides;
  updateSlider();
}

function createDots() {
  for (let i = 0; i < textSlides; i++) {
    const dot = document.createElement("span");
    dot.classList.add("dot");
    dot.addEventListener("click", () => {
      slideIndex = i;
      updateSlider();
    });
    dotsContainer.appendChild(dot);
  }
}

function updateDots() {
  const dots = document.querySelectorAll(".slider-dots .dot");
  dots.forEach((dot, i) => {
    dot.classList.toggle("active", i === slideIndex);
  });
}

// Auto-slide functionality
let sliderInterval = setInterval(slideTextNext, 5000);

// Pause auto-slide on hover
textSlider.parentElement.addEventListener("mouseenter", () => {
  clearInterval(sliderInterval);
});

textSlider.parentElement.addEventListener("mouseleave", () => {
  sliderInterval = setInterval(slideTextNext, 5000);
});

// Keyboard navigation
document.addEventListener("keydown", (e) => {
  if (e.key === "ArrowLeft") {
    slideTextPrev();
  } else if (e.key === "ArrowRight") {
    slideTextNext();
  }
});

// Initialize
createDots();
updateSlider();
</script>
