---
theme: jekyll-theme-primer
layout: sub-page
title: OSeMOSYS
permalink: /applications/
---
<section class="bg-gray-light container-lg p-responsive py-4 py-md-6 my-lg-6 fade-in-center">
  <div class="text-center">

  <h1 class="alt-h1 mb-4">Hundreds of OSeMOSYS Applications and Papers</h1>

  <div class="col-lg-10 mx-auto text-left">
    <p>OSeMOSYS is used around the world — from contributions to the <strong>IPCC</strong>, to <strong>UN</strong> and <strong>World Bank Group</strong> discussion papers, to official <strong>national planning</strong> documents and <strong>academic research</strong>.</p>

    <p>Explore a wide range of applications, spanning scholarly work, open data sets, and global to local case studies.</p>
  </div>

  <hr>

  <div class="col-lg-10 mx-auto text-left">
    <h2 class="alt-h2">Search and Explore</h2>
    <p>Recent applications can be found via the following links:</p>
    <ul>
      <li><a href="https://scholar.google.com/scholar?q=OSeMOSYS" target="_blank">Search scholarly applications</a></li>
      <li><a href="https://www.scopus.com" target="_blank">Browse last year’s general outputs</a></li>
      <li><a href="https://energydata.info" target="_blank">Access open data sets</a></li>
    </ul>
  </div>

  <hr>

  <div class="col-lg-10 mx-auto text-left">
    <h2 class="alt-h2">Remarkable Examples</h2>
    <p>Below are some high-impact projects powered by OSeMOSYS:</p>
  </div>

  <div class="slider-wrapper my-5">
    <div class="arrow arrow-left" onclick="slideTextPrev()">‹</div>

    <div class="slider-container">
      <div class="slider" id="textSlider">

        <div class="slide-card">
          <h3>OSeMOSYS Global</h3>
          <p><a href="https://osemosys-global.readthedocs.io/en/latest/" target="_blank">Open-source global electricity model</a></p>
        </div>

        <div class="slide-card">
          <h3>GENESYS-MOD</h3>
          <p><a href="https://git.tu-berlin.de/genesysmod/genesys-mod-public" target="_blank">Modular European decarbonisation model</a></p>
        </div>

        <div class="slide-card">
          <h3>TEMBA</h3>
          <p><a href="https://zenodo.org/records/3521841" target="_blank">The African electricity model base</a></p>
        </div>

        <div class="slide-card">
          <h3>OSeMBE</h3>
          <p><a href="https://github.com/HauHe/OSeMBE" target="_blank">Open Source energy Model – Base for Europe</a></p>
        </div>

        <div class="slide-card">
          <h3>SAMBA</h3>
          <p><a href="http://www.osemosys.org/samba.html" target="_blank">Southern African Model Base for Analysis</a></p>
        </div>

      </div>
    </div>

    <div class="arrow arrow-right" onclick="slideTextNext()">›</div>
  </div>

  <div class="slider-dots text-center mt-3" id="sliderDots"></div>

  <hr>

  <div class="col-lg-10 mx-auto text-left">
    <h2 class="alt-h2">Recommended Reading</h2>
    <p>For a broader analysis of applications and advancements in OSeMOSYS, see the following peer-reviewed publications:</p>

    <ol>
      <li><strong>Niet T, Shivakumar A, Gardumi F, Usher W, Williams E, Howells M.</strong><br>
      <em>Developing a community of practice around an open source energy modelling tool.</em><br>
      Energy Strategy Reviews, 2021.<br>
      <a href="https://doi.org/10.1016/j.esr.2021.100650" target="_blank">https://doi.org/10.1016/j.esr.2021.100650</a></li>

      <li><strong>Gardumi F, Shivakumar A, Morrison R, Taliotis C, Broad O, Beltramo A, et al.</strong><br>
      <em>From the development of an open-source energy modelling tool to its application and the creation of communities of practice: The example of OSeMOSYS.</em><br>
      Energy Strategy Reviews, 2018.<br>
      <a href="https://doi.org/10.1016/j.esr.2018.03.005" target="_blank">https://doi.org/10.1016/j.esr.2018.03.005</a></li>

      <li><strong>Plazas-Niño F, Tan N, Howells M, Foster V, Quirós-Tortós J.</strong><br>
      <em>Uncovering the applications... A systematic literature review.</em><br>
      Energy for Sustainable Development, 2025.<br>
      <a href="https://doi.org/10.1016/j.esd.2024.101629" target="_blank">https://doi.org/10.1016/j.esd.2024.101629</a></li>
    </ol>
  </div>

  <p class="mt-5"><a href="mailto:contact@osemosys.org">Have an application to showcase? Let us know →</a></p>

</div>
</section>

<!-- STYLES -->
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
}
.slider {
  display: flex;
  transition: transform 0.6s ease-in-out;
}
.slide-card {
  min-width: 100%;
  padding: 2rem;
  background: #f9f9f9;
  border-left: 5px solid #0066cc;
  box-shadow: 0 0 5px rgba(0,0,0,0.1);
  text-align: center;
}
.slide-card h3 {
  margin-bottom: 0.5rem;
}
.slide-card a {
  color: #0066cc;
  text-decoration: none;
  font-weight: 500;
}
.slide-card a:hover {
  text-decoration: underline;
}

.arrow {
  font-size: 2.5rem;
  cursor: pointer;
  user-select: none;
  padding: 0.5rem 1rem;
  color: #0066cc;
  background: #ffffffaa;
  border-radius: 6px;
  transition: background 0.3s ease;
}
.arrow:hover {
  background: #ffffff;
}
.arrow-left {
  position: absolute;
  left: -40px;
}
.arrow-right {
  position: absolute;
  right: -40px;
}

.slider-dots {
  display: flex;
  justify-content: center;
  gap: 10px;
  margin-top: 1rem;
}
.slider-dots .dot {
  width: 12px;
  height: 12px;
  background-color: #ccc;
  border-radius: 50%;
  cursor: pointer;
  transition: background-color 0.3s ease;
}
.slider-dots .dot.active {
  background-color: #0066cc;
}
</style>

<!-- SCRIPT -->
<script>
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

let sliderInterval = setInterval(slideTextNext, 4000);
textSlider.parentElement.addEventListener("mouseenter", () => clearInterval(sliderInterval));
textSlider.parentElement.addEventListener("mouseleave", () => sliderInterval = setInterval(slideTextNext, 4000));

createDots();
updateSlider();
</script>
