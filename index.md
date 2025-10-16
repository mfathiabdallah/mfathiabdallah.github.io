---
layout: page
title: Home
permalink: /
description: "Assistant Professor of Food Toxicology at Aarhus University, Denmark."
sitemap:
  lastmod: 2025-10-12
  exclude: 'no'
---

<!-- ===== Scrollable Navbar ===== -->
<div class="navbar-wrapper">
  <div class="nav-arrow left" onclick="scrollNavbar(-100)">&#10094;</div>
  <div class="navbar">
    <a href="/lab/">Lab</a>
    <a href="/research/">Research</a>
    <a href="/publications/">Publications</a>
    <a href="/news/">News</a>
    <a href="/contact/">Contact</a>
  </div>
  <div class="nav-arrow right" onclick="scrollNavbar(100)">&#10095;</div>
</div>

<br />

<!-- ===== Profile picture ===== -->
<img class="ProfilePic" img width="170" align="right" alt="Mohamed Fathi Abdallah" 
     style="float: right; margin-left: 28px; margin-up: 30px; border-radius: 10px; background-color: rgba(255, 255, 255, 0.5);" 
     src="mohamed_fathi_abdallah_2023(2).jpg">

<u>Short Bio (last update: September 2025)</u>

<h4>Current Position</h4>
- Assistant Professor in Food Toxicology, Department of Food Science, Aarhus University, Denmark.

<h4>Other positions and affiliations</h4>
- Advisory Expert for The Food Quality and Safety Control Innovation Team, Institute of Food Science
and Technology, Chinese Academy of Agricultural Sciences, Beijing, China.
- Board Member of the European Society of Toxicology In Vitro (ESTIV).
- Expert Group Member of ILSI Europe - Natural Toxins, Belgium.
- Member of Society of Toxicology (SOT) & Post-doctoral Representative of the SOT’s Food Safety Specialty (FS3), USA.

<!-- Education, Training & Working experience -->
<div>
  <h4>Previous Education, Training & Working experience</h4>
  <ul>
    <li>Former F.R.S-FNRS Postdoctoral Fellow (03/2024). Host institute University of Mons, Belgium.</li>
    <li>Former Postdoctoral Fellow (09/2023), Ghent University-Special Research Fund (BOF), Ghent University, Belgium.</li>
    <li>Former Researcher (09/2020), Teagasc Food Research Centre, Dublin, Ireland.</li>
    <li>PhD in Pharmaceutical Sciences (05/2020), Ghent University, Belgium.</li>
    <li>Master's Degree (04/2016) in Pharmaceutical Toxicology, Hacettepe University, Türkiye.</li>
    <li>Erasmus+ Exchange Master Student (03/2016), University of Natural Resources and Life Sciences, Vienna (BOKU), Austria.</li>
    <li>Erasmus+ Intern Researcher (12/2014), <i>IfADo</i> Institute, Dortmund, Germany.</li>
    <li>Bachelor's Degree (07/2011) in Veterinary Medical Sciences, Assiut University, Egypt.</li>
  </ul>
</div>

#### Research Interest
My research is centered on understanding the risks associated with natural toxins (mycotoxins and cyanotoxins) and other emerging contaminants in novel food. This is done by applying LC-MS/MS methods for detection. Also, through the use of _in vitro_ models, we investigate the effects of these toxins as mixtures on human health.
This interdisciplinary approach bridges food toxicology and human health, facilitating a comprehensive understanding of complex challenges.
<br />

<p style="color: red;">
We are open to support applications for scholarships and fellowships such as Marie Curie, DFF, Novo Nordisk Foundation, Villum Foundation, and others.
</p>

<h4>Areas of interest</h4>
<ul>
  <li>Detection of Natural Food Contaminantes (postgraduate students, PhDs, Postdoc).</li>
  <li>Application of Large Language Models in Food Contaminantes (only Postdoc or research assistants with solid experience in AI).</li>
  <li>Mixture toxicology with a focus on Food Contaminantes using NAMs (postgraduate students, PhDs, Postdoc).</li>
</ul>

<!-- ===== News Section ===== -->
<div>
  <hr />
  <h2>News</h2>
  <ul>
    {% for post in site.posts limit:5 %}
    <li><span style="font-weight: bold;">{{ post.date | date: "%Y-%m-%d" }}</span> - <a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
</div>

<!-- ===== Announcements Section ===== -->
<style>
  /* Announcement container for mobile stacking */
  @media (max-width: 768px) {
    .announcement-flex {
      flex-direction: column !important;
    }
    .announcement-flex > div {
      margin-right: 0 !important;
      margin-bottom: 15px;
    }
    .announcement-flex img {
      width: 100% !important;
      max-width: none !important;
      display: block;
      margin: 0 auto;
    }
  }

  /* Divider style */
  .centered-hr {
    width: 420px;
    margin: 40px auto;
    border: none;
    border-top: 2px solid #aaa;
  }
</style>

<!-- Announcement examples (repeat as before) -->
<div> <hr /> <h2>Announcements</h2>
  <!-- Announcement 1 -->
  <div class="announcement-flex" style="display: flex; flex-wrap: wrap;">
    <div style="flex: 1; margin-right: 50px; margin-bottom: 20px;">
      <h3>01 October 2025</h3>
      <p>PhD Vacancy in Food Toxicology at Food Science Department, Aarhus University</p>
      <p>Fully funded PhD position ...</p>
      <p>More info via the link <a href="https://phd.tech.au.dk/for-applicants/apply-here/saeropslag/advanced-mass-spectrometry-based-identification-and-quantification-of-natural-toxins-in-novel-food" target="_blank" rel="noopener">Click here</a>.</p>
    </div>
    <div style="flex: 1; margin-bottom: 20px;">
      <img src="/images/PhD announce.png" alt="PhD vacancy poster" style="width: 80%; max-width: 400px; border-radius: 20px;">
    </div>
  </div>
  <hr class="centered-hr" />
  <!-- Add remaining announcements similarly -->
</div>

<!-- ===== Contact Section ===== -->
<p style="text-align: left; font-weight: bold; margin-top: 30px;">For contact</p>

<div class="contact-grid">
  <div class="contact-card">
    <h4>Dr. Mohamed Fathi Abdallah</h4>
    <p style="word-wrap: break-word; overflow-wrap: anywhere;">
      <i class="fas fa-envelope"></i> &nbsp; Email: &nbsp;
      <a href="mailto:mfa@food.au.dk" target="_blank">mfa@food.au.dk</a><br>

      <i class="fab fa-twitter"></i> &nbsp; Twitter: &nbsp;
      <a href="https://twitter.com/MoFathiAbdallah" target="_blank">@MoFathiAbdallah</a><br>

      <i class="fab fa-linkedin"></i> &nbsp; LinkedIn: &nbsp;
      <a href="https://www.linkedin.com/in/mohamed-fathi-abdallah-66126a38/" target="_blank">
        Mohamed Fathi Abdallah
      </a><br>

      <img src="/images/AarhusUni.jpg" alt="Aarhus University"
           style="width: 85%; height: auto; border-radius: 10px; margin-top: 10px;">
    </p>
  </div>

  <div class="contact-card">
    <h4>Address:</h4>
    <p>
      Department of Food Science <br>
      Aarhus University <br>
      Agro Food Park 48, Aarhus, Denmark <br>
    </p>
    <iframe
      src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3080.8577236812416!2d10.153219677617567!3d56.19850617325248!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x464c15cd3e555c11%3A0xc10a2cd724a2185e!2sAgro%20Food%20Park%2048%2C%208200%20Aarhus!5e1!3m2!1sen!2sdk!4v1744464701594!5m2!1sen!2sdk"
      width="100%"
      height="225"
      style="border:0; border-radius:10px;"
      allowfullscreen=""
      loading="lazy"
      referrerpolicy="no-referrer-when-downgrade">
    </iframe>
  </div>
</div>

<!-- ===== Visitors Map ===== -->
<div style="display: flex; justify-content: center; margin: 20px 0;">
  <a href="https://mapmyvisitors.com/web/1bvu3" title="Visit tracker">
    <img src="https://mapmyvisitors.com/map.png?d=kutvpm4t6Qxf4czmSsSz26dA5aYOrP3YLbkGJi-uHv8&cl=ffffff" 
         alt="Visitor tracker map" style="max-width: 300px; height: auto; border-radius: 8px;">
  </a>
</div>

<hr class="centered-hr" />

<!-- ===== Scroll Navbar JS ===== -->
<script>
function scrollNavbar(distance) {
  const navbar = document.querySelector('.navbar');
  navbar.scrollBy({ left: distance, behavior: 'smooth' });
}
</script>

<!-- ===== Scroll Navbar CSS ===== -->
<style>
/* Navbar wrapper with arrows */
.navbar-wrapper {
  position: relative;
  overflow: hidden;
  width: 100%;
}

/* Scrollable navbar */
.navbar {
  display: flex;
  gap: 20px;
  padding: 10px 0;
  white-space: nowrap;
  overflow-x: auto;
  -webkit-overflow-scrolling: touch;
  scroll-behavior: smooth;
}

.navbar a {
  flex: 0 0 auto;
  text-decoration: none;
  padding: 8px 15px;
  border-radius: 5px;
  background-color: #eee;
  color: #333;
  font-weight: bold;
  transition: 0.3s;
}

.navbar a:hover {
  background-color: #ccc;
}

/* Hide scrollbar */
.navbar::-webkit-scrollbar {
  display: none;
}

/* Arrow buttons */
.nav-arrow {
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
  width: 30px;
  height: 40px;
  background-color: rgba(255,255,255,0.8);
  border-radius: 5px;
  display: flex;
  align-items: center;
  justify-content: center;
  cursor: pointer;
  z-index: 10;
  font-weight: bold;
  font-size: 20px;
  user-select: none;
}

.nav-arrow.left {
  left: 5px;
}

.nav-arrow.right {
  right: 5px;
}

/* Hide arrows on desktop */
@media (min-width: 769px) {
  .nav-arrow {
    display: none;
  }
}
</style>
