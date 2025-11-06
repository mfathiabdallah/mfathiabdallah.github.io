---
layout: page
title: "Join us"
---

<!-- Font Awesome for icons -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

<!-- ========================= -->
<!-- PhD Hiring Card -->
<div class="opportunity-card phd-card">
  <h2><i class="fa-solid fa-rocket icon-accent"></i> We’re Hiring a PhD Student!</h2>
  <p>
    <strong>Topic:</strong> Quantification of natural toxins in novel food using advanced mass spectrometry.<br>
    <strong>Deadline:</strong> <span class="deadline-text">6 November 2025</span>
  </p>
  <div class="card-buttons">
    <a href="https://www.mfathiabdallah.com/PhD_position1/" target="_blank" rel="noopener" class="btn btn-primary">
      <i class="fa-solid fa-magnifying-glass"></i> View Details
    </a>
    <a href="https://phd.tech.au.dk/for-applicants/apply-here/saeropslag/advanced-mass-spectrometry-based-identification-and-quantification-of-natural-toxins-in-novel-food" target="_blank" rel="noopener" class="btn btn-secondary">
      <i class="fa-solid fa-compass"></i> Apply Now
    </a>
  </div>
</div>

<!-- ========================= -->
<!-- Master Thesis / Internship Opportunities -->
<div class="opportunity-card master-card">
  <h3><i class="fa-solid fa-graduation-cap icon-accent"></i> Master Thesis / Internship Opportunities</h3>
  <p>We welcome motivated Master students, interns, or Erasmus students to join our research projects.</p>

  <ul class="project-list">
    <li>
      <strong>Mixture Toxicology:</strong>
      <p>Optimization of a 3D in vitro model to study hepatocytotoxicity of different food contaminants</p>
      <a href="https://food.au.dk/masters-thesis-projects/optimization-of-a-3d-in-vitro-model-to-study-the-hepatocytotoxicity-of-different-food-contaminants" class="btn btn-outline">
        View Project
      </a>
    </li>
    <li>
      <strong>Food AI & Database:</strong>
      <p>Developing a database of microbial food toxins in the EU (case study on mycotoxins)</p>
      <a href="https://food.au.dk/masters-thesis-projects/developing-a-database-of-microbial-food-toxins-in-the-eu-case-study-on-mycotoxins" class="btn btn-outline">
        View Project
      </a>
    </li>
  </ul>

  <p>Interns or Erasmus thesis students are welcome!<br>
  For more information, please contact <strong>Dr. Mohamed Fathi Abdallah</strong> at <a href="mailto:mfa@food.au.dk">mfa@food.au.dk</a>.</p>
</div>

<!-- ========================= -->
<!-- Open Opportunities -->
<div class="collapsible-section">
  <h3 class="collapsible-title"><i class="fa-solid fa-arrow-right"></i> Open Opportunities</h3>
  <div class="collapsible-content">
    <ul>
      <li>Marie Skłodowska-Curie Fellowships</li>
      <li>Funding from Novo Nordisk Foundation, DFF, Villum Foundation</li>
      <li>Other national or international fellowships</li>
    </ul>
    <p>If you are a motivated researcher interested in food toxicology, mixture risk assessment, or AI-based safety evaluation — <strong>reach out to discuss collaboration opportunities</strong>.</p>
  </div>
</div>

<!-- ========================= -->
<!-- Styles -->
<style>
/* Base Colors & Fonts */
:root {
  --accent: #004aad;
  --accent-light: #f4f8ff;
  --secondary: #e55300;
  --shadow: rgba(0,0,0,0.08);
  --font: "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
}

/* Typography */
body {
  font-family: var(--font);
  color: #222;
  line-height: 1.65;
}
h2, h3, h4 {
  color: var(--accent);
  margin-top: 0;
}
p, li {
  font-size: 1.05em;
}

/* Icon accent */
.icon-accent {
  color: var(--accent);
  margin-right: 6px;
}

/* Opportunity Cards - Modern with Gradient Border */
.opportunity-card {
  border-radius: 12px;
  padding: 25px 22px;
  margin: 35px 0;
  box-shadow: 0 4px 14px var(--shadow);
  transition: transform 0.2s ease, box-shadow 0.2s ease;
  position: relative;
  background: var(--accent-light);
  border-left: 6px solid var(--accent);
}
.opportunity-card:hover {
  transform: translateY(-3px);
  box-shadow: 0 6px 20px var(--shadow);
}

/* Specific Cards */
.phd-card {
  border-left-color: rgba(0, 74, 173, 0.9);
}
.master-card {
  border-left-color: rgba(0, 74, 173, 0.6);
}

/* Buttons */
.btn {
  display: inline-block;
  padding: 10px 18px;
  border-radius: 8px;
  font-weight: 600;
  text-decoration: none;
  transition: all 0.25s ease;
  margin-top: 10px;
}
.btn-primary {
  background-color: var(--accent);
  color: white;
}
.btn-primary:hover {
  background-color: #0066cc;
}
.btn-secondary {
  background-color: var(--secondary);
  color: white;
}
.btn-secondary:hover {
  background-color: #cc4400;
}
.btn-outline {
  background-color: transparent;
  border: 2px solid var(--accent);
  color: var(--accent);
}
.btn-outline:hover {
  background-color: rgba(0,74,173,0.1);
}

/* Project list */
.project-list {
  list-style-type: none;
  padding-left: 0;
}
.project-list li {
  margin-bottom: 20px;
}

/* Deadline */
.deadline-text {
  color: #d12a00;
  font-weight: 600;
}

/* Collapsible Section */
.collapsible-title {
  cursor: pointer;
  font-size: 1.25em;
  font-weight: 600;
  padding: 12px 18px;
  border-radius: 8px;
  background: linear-gradient(90deg, var(--accent) 0%, #007bff 100%);
  color: white;
  margin-bottom: 8px;
  transition: all 0.3s ease;
  box-shadow: 0 3px 10px var(--shadow);
}
.collapsible-title:hover {
  transform: translateY(-2px);
  background: linear-gradient(90deg, #003b9b 0%, #0066cc 100%);
}
.collapsible-content {
  padding: 14px 18px;
  display: block; /* Change to none for default collapse */
  border-left: 4px solid rgba(0, 74, 173, 0.3);
  margin-bottom: 20px;
  border-radius: 6px;
  background-color: var(--accent-light);
  transition: max-height 0.3s ease;
}

/* Hover subtle highlight for all cards and links */
.opportunity-card:hover, .btn-outline:hover {
  cursor: pointer;
}

/* Responsive */
@media (max-width:900px) {
  .opportunity-card { padding: 20px 18px; }
  .project-list li { margin-bottom: 16px; }
}
@media (max-width:480px) {
  .btn { width: 100%; margin-bottom: 10px; }
  .project-list li { margin-bottom: 14px; }
}
</style>

<!-- ========================= -->
<!-- Collapsible JS -->
<script>
document.querySelectorAll('.collapsible-title').forEach(title => {
  title.addEventListener('click', () => {
    const content = title.nextElementSibling;
    content.style.display = content.style.display === 'block' ? 'none' : 'block';
  });
});
</script>
