---
layout: page
title: "Join us"
---

<!-- Font Awesome -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

<!-- ========================= -->
<!-- Open Opportunities -->
<div class="section-card">
  <h3 class="section-title">
    <i class="fa-solid fa-arrow-right"></i> Open Opportunities
  </h3>

  <div class="section-content">
    <ul>
      <li>Marie Skłodowska-Curie Fellowships</li>
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
<div class="section-card">
  <h3 class="section-title">
    <i class="fa-solid fa-rocket"></i> We’re Hiring a PhD Student!
  </h3>

  <div class="section-content">
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
<div class="section-card">
  <h3 class="section-title">
    <i class="fa-solid fa-graduation-cap"></i> Master Thesis / Internship Opportunities
  </h3>

  <div class="section-content">
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
    </ul>

    <p>
      Interns or Erasmus thesis students are welcome.<br>
      Contact <strong>Dr. Mohamed Fathi Abdallah</strong> at
      <a href="mailto:mfa@food.au.dk">mfa@food.au.dk</a>.
    </p>
  </div>
</div>

<!-- ========================= -->
<!-- Styles -->
<style>
:root {
  --accent: #004aad;
  --secondary: #e55300;
  --light: #f4f8ff;
  --shadow: rgba(0,0,0,0.08);
  --font: "Segoe UI", Roboto, Arial, sans-serif;
}

body {
  font-family: var(--font);
  color: #222;
  line-height: 1.65;
}

/* Unified section card */
.section-card {
  margin: 35px 0;
  box-shadow: 0 4px 14px var(--shadow);
  border-radius: 10px;
  overflow: hidden;
  background: white;
}

/* Unified header (same for all) */
.section-title {
  margin: 0;
  padding: 14px 20px;
  font-size: 1.25em;
  font-weight: 600;
  color: white;
  background: linear-gradient(90deg, var(--accent), #007bff);
}

.section-title i {
  margin-right: 8px;
}

/* Content */
.section-content {
  padding: 20px 22px;
  background: var(--light);
}

p, li {
  font-size: 1.05em;
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
  background: var(--accent);
  color: white;
}
.btn-primary:hover {
  background: #0066cc;
}

.btn-secondary {
  background: var(--secondary);
  color: white;
}
.btn-secondary:hover {
  background: #cc4400;
}

.btn-outline {
  border: 2px solid var(--accent);
  color: var(--accent);
  background: transparent;
}
.btn-outline:hover {
  background: rgba(0,74,173,0.1);
}

/* Button row */
.button-row {
  display: flex;
  gap: 12px;
  flex-wrap: wrap;
}

/* Projects */
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

/* Responsive */
@media (max-width: 600px) {
  .btn {
    width: 100%;
  }
}
</style>
