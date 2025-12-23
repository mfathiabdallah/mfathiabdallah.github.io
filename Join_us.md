---
layout: page
title: ""
---

<!-- Font Awesome -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

<!-- ========================= -->
<!-- Page Header / Hero -->
<div class="hero-banner">
  <h1>Join Our Research Group</h1>
  <p>
    Explore PhD, Master, and Internship opportunities in food toxicology,
    mixture risk assessment, and AI-based food safety evaluation.
  </p>
</div>

<!-- ========================= -->
<!-- Open Opportunities -->
<div class="collapsible">
  <h1 class="collapsible-title">
    <i class="fa-solid fa-briefcase"></i> Open Opportunities
  </h1>
  <div class="collapsible-content">
    <ul>
       <li>Marie Curie Fellowships</li>
       <li>Funding from Novo Nordisk Foundation, DFF, Villum Foundation</li>
       <li>Other national or international fellowships</li>
    </ul>
    <p>
      If you are a motivated researcher interested in food toxicology,
      mixture risk assessment, or AI-based safety evaluation —
      <strong>reach out to discuss collaboration opportunities</strong>.
    </p>
  </div>
</div>

<!-- ========================= -->
<!-- PhD Hiring -->
<div class="collapsible">
  <h1 class="collapsible-title">
    <i class="fa-solid fa-rocket"></i> We’re Hiring a PhD Student!
  </h1>
  <div class="collapsible-content">
    <p>
      <strong>Topic:</strong> Quantification of natural toxins in novel food using advanced mass spectrometry.<br>
      <strong>Deadline:</strong> <span class="deadline-text">6 November 2025</span>
    </p>
    <div class="button-row">
      <a href="https://www.mfathiabdallah.com/PhD_position1/" target="_blank" rel="noopener" class="btn btn-primary">
        <i class="fa-solid fa-magnifying-glass"></i> View Details
      </a>
      <a href="https://phd.tech.au.dk/for-applicants/apply-here/saeropslag/advanced-mass-spectrometry-based-identification-and-quantification-of-natural-toxins-in-novel-food"
         target="_blank" rel="noopener" class="btn btn-secondary">
        <i class="fa-solid fa-compass"></i> Apply Now
      </a>
    </div>
  </div>
</div>

<!-- ========================= -->
<!-- Master / Internship -->
<div class="collapsible">
  <h1 class="collapsible-title">
    <i class="fa-solid fa-microscope"></i> Master Thesis / Internship Opportunities
  </h1>
  <div class="collapsible-content">
    <p>
      We welcome motivated Master students, interns, or Erasmus students
      to join our research projects.
    </p>
    <ul class="project-list">
      <li>
        <strong>Mixture Toxicology</strong>
        <p>
          Optimization of a 3D in vitro model to study hepatocytotoxicity
          of different food contaminants
        </p>
        <a href="https://food.au.dk/masters-thesis-projects/optimization-of-a-3d-in-vitro-model-to-study-the-hepatocytotoxicity-of-different-food-contaminants"
           class="btn btn-outline">
          View Project
        </a>
      </li>
      <li>
        <strong>Food AI & Database</strong>
        <p>
          Developing a database of microbial food toxins in the EU
          (case study on mycotoxins)
        </p>
        <a href="https://food.au.dk/masters-thesis-projects/developing-a-database-of-microbial-food-toxins-in-the-eu-case-study-on-mycotoxins"
           class="btn btn-outline">
          View Project
        </a>
      </li>
      <li>
        <p>
          Interns or Erasmus thesis students are welcome.<br>
          Contact <strong>Dr. Mohamed Fathi Abdallah</strong> at
          <a href="mailto:mfa@food.au.dk">mfa@food.au.dk</a>.
        </p>
      </li>
    </ul>
  </div>
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
  margin: 0 0 10px;
  font-weight: 600;
  color: #ffffff;
}
.hero-banner p {
  font-size: 1.1em;
  max-width: 820px;
  margin: 10px auto 0;
  color: #f2f6f9;
}

/* Collapsible Sections (Card Style) */
.collapsible-title {
  background: linear-gradient(90deg, #0b3c5d, #1f7a8c);
  color: #ffffff;
  padding: 12px 18px;
  border-radius: 12px;
  font-size: 1.25em;
  margin-bottom: 12px;
}
.collapsible-title i {
  margin-right: 8px;
}
.collapsible-content {
  background: rgba(255,255,255,0.95); /* slightly transparent card */
  padding: 20px;
  border-radius: 12px;
  margin-bottom: 30px;
  box-shadow: 0 6px 20px rgba(0,0,0,0.08);
  width: 100%;
  overflow: hidden;
}

/* Buttons */
.btn {
  display: inline-block;
  padding: 10px 18px;
  border-radius: 8px;
  font-weight: 600;
  text-decoration: none;
  margin-top: 10px;
  transition: all 0.2s ease;
}
.btn-primary {
  background: #0b3c5d;
  color: white;
}
.btn-primary:hover {
  background: #1f7a8c;
}
.btn-secondary {
  background: #e55300;
  color: white;
}
.btn-secondary:hover {
  background: #cc4400;
}
.btn-outline {
  border: 2px solid #0b3c5d;
  color: #0b3c5d;
  background: transparent;
}
.btn-outline:hover {
  background: rgba(11,60,93,0.1);
}

/* Project list */
.project-list {
  list-style: none;
  padding-left: 0;
}
.project-list li {
  padding: 16px 0;
  border-bottom: 1px solid rgba(0,0,0,0.08);
}
.project-list li:last-child {
  border-bottom: none;
}

/* Deadline */
.deadline-text {
  color: #d12a00;
  font-weight: 600;
}

/* =========================
   Mobile-Friendly Fix
   ========================= */
@media (max-width: 768px) {
  .button-row {
    display: flex;
    flex-direction: column;
    gap: 10px;
  }
  .button-row .btn,
  .project-list li .btn {
    width: 100%;
    text-align: center;
    margin-top: 0;
  }
  .hero-banner {
    padding: 30px 15px;
  }
  .collapsible-content {
    padding: 16px 14px;
  }
  .project-list,
  .collapsible-content ul {
    padding-left: 0;
    margin-left: 0;
  }
}
@media (max-width: 600px) {
  .btn {
    font-size: 1em;
  }
}
</style>
