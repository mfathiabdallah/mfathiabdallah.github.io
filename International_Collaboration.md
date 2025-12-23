---
layout: page
title: ""
---
<!-- Font Awesome for icons -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

<!-- ========================= -->
<!-- Hero Banner -->
<div class="hero-banner">
  <h1>International Collaboration</h1>
  <p>
    Overview of international collaborations.
  </p>
</div>

<!-- ========================= -->
<!-- International Collaboration -->
<div class="card">
  <h1 class="collapsible-title">
    <i class="fas fa-globe"></i> International Collaboration
  </h1>
  <p class="card-subtitle">Active collaborations based on projects and research papers.</p>
  <ul>
    <strong style="font-size: larger; text-decoration: underline; color: red;">Europe</strong>
    <li>University of Veterinary Medicine Vienna, <strong>Austria</strong></li>
    <li>University of Vienna, <strong>Austria</strong></li>
    <li>Ghent University, <strong>Belgium</strong></li>
    <li>University of Parma, <strong>Italy</strong></li>
    <li>Sciensano Institute, Tervuren, <strong>Belgium</strong></li>
    <strong style="font-size: larger; text-decoration: underline; color: red;">Asia</strong>
    <li>Institute of Food Science and Technology, Beijing, <strong>PR China</strong></li>
    <li>University of Chinese Academy of Sciences, Shanghai, <strong>PR China</strong></li>
    <li>Institute for Agri-Food Standards and Testing Technology, Shanghai, <strong>PR China</strong></li>
    <li>Istanbul University, Istanbul, <strong>Türkiye</strong></li>
  </ul>
</div>

<!-- ========================= -->
<!-- Styles -->
<style>
/* =========================
   Global Settings
   ========================= */
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
body {
  font-family: "Segoe UI", Roboto, Arial, sans-serif;
  color: #222;
  line-height: 1.65;
  overflow-x: hidden;
  background: #f8f9fa; /* light overall background */
}

/* Hero Banner */
.hero-banner {
  background: linear-gradient(135deg, #0b3c5d, #1f7a8c);
  color: #ffffff;
  padding: 50px 30px;
  border-radius: 12px;
  text-align: center;
  margin-bottom: 35px;
  box-shadow: 0 8px 20px rgba(0,0,0,0.15);
}
.hero-banner h1 {
  font-size: 2.4em;
  margin-bottom: 10px;
  font-weight: 600;
  color: #ffffff; /* make the title white */
}
.hero-banner p {
  font-size: 1.1em;
  max-width: 820px;
  margin: 0 auto;
  color: #f2f6f9;
}

/* Cards */
.card {
  background: rgba(255,255,255,0.95);
  color: #222;
  padding: 20px 22px 22px 22px; /* top, right, bottom, left */
  border-radius: 12px;
  box-shadow: 0 6px 20px rgba(0,0,0,0.08);
  margin-bottom: 25px;
  border-left: none; /* explicitly remove any left border */
}

/* Card Titles & Subtitles */
.card-title {
  font-size: 1.8em;
  font-weight: 600;
  margin-bottom: 8px;
}
.card-subtitle {
  font-size: 1.05em;
  color: #555;
  margin-top: 14px; /* add some space above */
  margin-bottom: 15px;
}

/* Card Links */
.card-link {
  text-decoration: none;
  color: #222;
}
.card-link:hover {
  color: #0b3c5d;
  text-decoration: underline;
}

/* Lists */
.card ul {
  list-style-type: disc;
  padding-left: 20px;
  line-height: 1.6;
}

/* Responsive */
@media (max-width: 768px) {
  .hero-banner { padding: 30px 15px; }
}

/* Collapsible-style section titles (like Join Us page) */
.collapsible-title {
  background: linear-gradient(90deg, #0b3c5d, #1f7a8c);
  color: #ffffff;
  padding: 12px 18px;
  border-radius: 12px;
  font-size: 1.25em;
  margin-bottom: 6px 0 6px 0; /* top 6px, bottom 6px */
}
.collapsible-title i {
  margin-right: 8px;
}
</style>


