---
layout: page
title: "Lab and Research"
---

## About AU FOOD TOX

At AU FOOD Department, our research is centered on understanding the risks associated with natural toxins (mycotoxins and cyanotoxins) and other emerging contaminants in novel food. This is done by applying LC-MS/MS methods for detection. Also, through the use of in vitro models, we investigate the effects of these toxins as mixtures on human health. This interdisciplinary approach bridges food toxicology and human health, facilitating a comprehensive understanding of complex challenges. 

<!-- Research Overview Banner -->
<figure class="research-overview">
  <img src="/images/aufoodtox.png" alt="AU FOOD TOX" width="1000">
  <figcaption><em>A schematic overview of AU FOOD TOX group's research focus.</em></figcaption>
</figure>

<!-- ========================= -->
<!-- 🧪 Research Lines -->
<div class="collapsible">
  <h1 class="collapsible-title">&#10148; 🧪 Research Lines</h1>
  <div class="collapsible-content">
    <h3>A) Natural Toxins in Food</h3>
    <p>Detection and occurrence of mycotoxins and cyanotoxins in food products using LC-MS/MS and targeted/non-targeted analysis.</p>
    <p><strong>Related publications:</strong></p>
    <ul>
      <li>WR Van Hassel, <strong>MF Abdallah</strong>, MG Velasquez, C Miles, I Samdal, J Masquelier, A Rajkovic (2024). Experimental accumulation and depuration kinetics and natural occurrence of microcystin-LR in basil (<em>Ocimum basilicum L.</em>). <em>Environmental Pollution</em>, 123715. <a href="https://www.sciencedirect.com/science/article/abs/pii/S0269749124004299?via%3Dihub" target="_blank" rel="noopener">Link</a></li>
    </ul>

    <h3>B) Mixture Toxicology, Risk Assessment & Human Health</h3>
    <p>Investigating combined toxic effects of multiple food contaminants using in vitro models and New Approach Methodologies (NAMs).</p>
    <p><strong>Related publications:</strong></p>
    <ul>
      <li>M Suman, M Oboeuf, <strong>MF Abdallah</strong>, C Hazel, E Varga, A Mally, A Medina, M Molero, A Sansom, and KJ Korzeniowski (2025). Framework on risk prioritisation of mycotoxins in food: a case study in two wheat-based products. <em>World Mycotoxin Journal</em>. <a href="https://brill.com/view/journals/wmj/aop/article-10.1163-18750796-bja10027/article-10.1163-18750796-bja10027.xml" target="_blank" rel="noopener">Link</a></li>
    </ul>

    <h3>C) Artificial Intelligence in Food Toxicology</h3>
    <p>Applying AI and large language models for risk prediction, data integration, and contaminant classification.</p>
    <p><strong>Related publications:</strong> Add soon.</p>
  </div>
</div>

<!-- ========================= -->
<!-- 💰 Funding and Support -->
<div class="collapsible">
  <h1 class="collapsible-title">&#10148; 💰 Funding and Support</h1>
  <div class="collapsible-content">
    <p>Our research activities are supported by competitive national and international funding sources. We are grateful to these foundations and programs for supporting our mission to advance food toxicology and safety research.</p>
    
    <!-- Centered Logos -->
    <div class="image-container">
      <img src="/images/novonordiskfoundation.jpg" alt="Novo Nordisk Foundation">
    </div>
  </div>
</div>

<!-- ========================= -->
<!-- 🧾 Current Projects -->
<div class="collapsible">
  <h1 class="collapsible-title">&#10148; 🧾 Current Projects</h1>
  <div class="collapsible-content">
    <table class="full-width-table">
      <thead>
        <tr>
          <th>Project</th>
          <th>Funding Agency</th>
          <th>Period</th>
          <th>Role</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td><strong>ToxiFOOD</strong></td>
          <td><img src="/images/novonordiskfoundationlogo.png" alt="Novo Nordisk Foundation"></td>
          <td>2026 – 2031</td>
          <td>PI</td>
        </tr>
      </tbody>
    </table>
  </div>
</div>

<!-- ========================= -->
<!-- 🎯 Open Opportunities -->
<div class="collapsible">
  <h1 class="collapsible-title">&#10148; 🎯 Open Opportunities</h1>
  <div class="collapsible-content">
    <p>We are open to collaborate on and support new applications for <strong>Marie Skłodowska-Curie</strong>, <strong>Novo Nordisk Foundation</strong>, <strong>DFF</strong>, <strong>Villum Foundation</strong>, and other national or international fellowships.</p>
    <p>If you are a motivated researcher interested in food toxicology, mixture risk assessment, or AI-based safety evaluation — <strong>reach out to discuss collaboration opportunities</strong>.</p>
  </div>
</div>

<!-- ========================= -->
<!-- 👩‍🔬 Lab Members -->
<div class="collapsible">
  <h1 class="collapsible-title">&#10148; 👩‍🔬 Lab Members</h1>
  <div class="collapsible-content">
    <table class="full-width-table">
      <thead>
        <tr>
          <th>Name</th>
          <th>Position</th>
          <th>Research Focus</th>
          <th>Contact</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td><strong>Dr. Mohamed Fathi Abdallah</strong></td>
          <td>Principal Investigator</td>
          <td>Food toxicology, natural toxins, LC-MS/MS</td>
          <td>mfa@food.au.dk</td>
        </tr>
      </tbody>
    </table>
  </div>
</div>

<!-- ========================= -->
<!-- JS for collapsible -->
<script>
function toggleCollapsible(event) {
  const content = event.target.nextElementSibling;
  event.target.classList.toggle("active");
  if (content.style.maxHeight){
    content.style.maxHeight = null;
  } else {
    content.style.maxHeight = content.scrollHeight + "px";
  }
}

const collapsibleTitles = document.getElementsByClassName("collapsible-title");
for (let i = 0; i < collapsibleTitles.length; i++) {
  collapsibleTitles[i].addEventListener("click", toggleCollapsible);
}
</script>

<!-- ========================= -->
<!-- CSS -->
<style>
.collapsible-title {
  color: #10148;
  cursor: pointer;
  font-size: 25px;
  font-weight: bold;
  padding: 7.5px;
  border-radius: 0px;
  background-color: #ccc;
  text-align: left;
  margin-bottom: 20px;
}

.collapsible-content {
  overflow: hidden;
  transition: max-height 0.3s ease;
}

.full-width-table {
  width: 100%;
  border-collapse: collapse;
  margin: 0 auto;
}

.full-width-table th, 
.full-width-table td {
  border: 1px solid #ddd;
  padding: 12px;
  text-align: center;
  vertical-align: middle;
}

.full-width-table th {
  background-color: #f8f8f8;
}

.full-width-table img {
  display: block;
  margin: 0 auto;
  max-width: 120px;
}

.image-container {
  display: flex;
  justify-content: center;
  align-items: center;
  margin-top: 15px;
}

.image-container img {
  max-width: 600px;
  height: auto;
  border-radius: 6px;
  box-shadow: 0 2px 5px rgba(0,0,0,0.08);
  margin: 0 10px;
  transition: transform 0.2s ease;
}
</style>
