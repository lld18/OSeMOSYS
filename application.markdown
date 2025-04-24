---
theme: jekyll-theme-primer
layout: sub-page
title: OSeMOSYS
permalink: /applications/
---

# Hundreds of OSeMOSYS Applications and Papers

OSeMOSYS is used around the world — from contributions to the **IPCC**, to **UN** and **World Bank Group** discussion papers, to **official national planning** documents and **academic research**.

Explore a wide range of applications, spanning scholarly work, open data sets, and global to local case studies.

---

## Search and Explore

Recent applications can be found via the following links:

- [Search scholarly applications](https://scholar.google.com/scholar?q=OSeMOSYS)
- [Browse last year’s general outputs](https://www.scopus.com)
- [Access open data sets](https://energydata.info)

---

## Remarkable Examples

Below are some high-impact projects powered by OSeMOSYS:

<div class="slider-container my-5">
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

<style>
.slider-container {
  max-width: 720px;
  margin: 0 auto;
  overflow: hidden;
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
</style>
<script>
let slideIndex = 0;
const textSlider = document.getElementById("textSlider");
const textSlides = textSlider.children.length;

let sliderInterval = setInterval(slideTextNext, 4000);

function slideTextNext() {
  slideIndex = (slideIndex + 1) % textSlides;
  textSlider.style.transform = `translateX(-${slideIndex * 100}%)`;
}

// Pause on hover
textSlider.parentElement.addEventListener("mouseenter", () => {
  clearInterval(sliderInterval);
});

textSlider.parentElement.addEventListener("mouseleave", () => {
  sliderInterval = setInterval(slideTextNext, 4000);
});
</script>
---

## Recommended Reading

For a broader analysis of applications and advancements in OSeMOSYS, see the following peer-reviewed publications:

1. **Niet T, Shivakumar A, Gardumi F, Usher W, Williams E, Howells M.**  
   _Developing a community of practice around an open source energy modelling tool._  
   *Energy Strategy Reviews*, 2021.  
   [https://doi.org/10.1016/j.esr.2021.100650](https://doi.org/10.1016/j.esr.2021.100650)

2. **Gardumi F, Shivakumar A, Morrison R, Taliotis C, Broad O, Beltramo A, et al.**  
   _From the development of an open-source energy modelling tool to its application and the creation of communities of practice: The example of OSeMOSYS._  
   *Energy Strategy Reviews*, 2018.  
   [https://doi.org/10.1016/j.esr.2018.03.005](https://doi.org/10.1016/j.esr.2018.03.005)

3. **Plazas-Niño, F., Tan, N., Howells, M., Foster, V., & Quirós-Tortós, J.**  
   _Uncovering the applications, developments, and future research directions of the open-source energy modelling system (OSeMOSYS): A systematic literature review._  
   *Energy for Sustainable Development*, 2025.  
   [https://doi.org/10.1016/j.esd.2024.101629](https://doi.org/10.1016/j.esd.2024.101629)

---

Have an application to showcase? [Let us know](mailto:contact@osemosys.org)!