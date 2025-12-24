---
title: ""
layout: page
sitemap:
  lastmod: 2025-12-14
  exclude: 'no'
---

<!-- ========================= -->
<!-- Contact -->
<div class="content-box" style="margin-top:30px;">
  <h3 class="section-title"><i class="fa-solid fa-paper-plane"></i> Contact</h3>

  <div class="contact-grid">
    <div class="contact-card">
      <h4><i class="fa-solid fa-user-tie"></i> Dr. Mohamed Fathi Abdallah</h4>
      <p>
        <i class="fa-solid fa-envelope"></i> Email: <a href="mailto:mfa@food.au.dk">mfa[at]food.au.dk</a><br>
        <i class="fa-brands fa-x-twitter"></i> Twitter: <a href="https://twitter.com/MoFathiAbdallah" target="_blank">@MoFathiAbdallah</a><br>
        <i class="fa-brands fa-linkedin"></i> LinkedIn: <a href="https://www.linkedin.com/in/mohamed-fathi-abdallah-66126a38/" target="_blank">Mohamed Fathi Abdallah</a>
      </p>
      <img src="/images/AarhusUni.jpg" alt="Aarhus University" class="contact-img">
    </div>

    <div class="contact-card">
      <h4><i class="fa-solid fa-location-dot"></i> Address</h4>
      <p>
        Department of Food Science<br>
        Aarhus University<br>
        Agro Food Park 48, Aarhus, Denmark
      </p>
      <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3080.8577236812416!2d10.153219677617567!3d56.19850617325248!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x464c15cd3e555c11%3A0xc10a2cd724a2185e!2sAgro%20Food%20Park%2048%2C%208200%20Aarhus!5e1!3m2!1sen!2sdk!4v1744464701594!5m2!1sen!2sdk"
        width="100%" height="225" style="border:0; border-radius:10px;" allowfullscreen loading="lazy"></iframe>
    </div>
  </div>
</div>

<!-- ========================= -->
<!-- Visitors Map -->
<hr class="centered-hr" />
<div style="text-align:center; margin-bottom:40px;">
  <a href="https://mapmyvisitors.com/web/1bvu3" title="Visit tracker">
    <img src="https://mapmyvisitors.com/map.png?d=kutvpm4t6Qxf4czmSsSz26dA5aYOrP3YLbkGJi-uHv8&cl=ffffff" alt="Visitor tracker map" style="max-width:300px; border-radius:8px;">
  </a>
</div>

<!-- ========================= -->
<!-- ✅ CSS -->
<style>
:root {
  --accent:#0b3c5d;
  --muted:#555;
  --card-shadow:0 4px 14px rgba(0,0,0,0.08);
}

.icon-accent { color:var(--accent); margin-right:6px; }


/* Section titles */
.section-title {
  color:#fff;
  background: linear-gradient(90deg, #0b3c5d, #1f7a8c);
  padding:10px 12px;
  border-radius:8px;
  font-size:1.25rem;
  display:flex;
  align-items:center;
  gap:8px;
  margin-bottom:10px;
}

/* NEW flag inside the title */
.section-title .new-flag {
  background:linear-gradient(135deg,#ff3b3b,#ff7b00);
  color:#fff; font-size:0.8rem; font-weight:700;
  padding:4px 10px; border-radius:6px;
  animation:pulse 1.5s infinite ease-in-out;
  box-shadow:0 0 6px rgba(255,90,0,0.4);
}
@keyframes pulse { 0%{transform:scale(1)} 50%{transform:scale(1.1)} 100%{transform:scale(1)} }

/* Content boxes */
.content-box { margin-top:20px; padding:18px; border-radius:12px; box-shadow:var(--card-shadow); background:rgba(255,255,255,0.05); }

/* Announcements */
.announcement-item {
  display:flex; flex-wrap:nowrap; align-items:center; gap:16px;
  background:rgba(255,255,255,0.04); padding:12px; border-radius:10px;
  box-shadow:0 2px 8px rgba(0,0,0,0.05);
  transition:transform .18s ease-in-out;
}
.announcement-item:hover { transform:translateY(-3px); }
.announcement-text { flex:1; min-width:220px; }
.announcement-text h3 { margin:0 0 4px; color:var(--accent); font-weight:400; font-size:1.03rem; }
.announcement-text p { margin:0 0 6px; line-height:1.45; color:#333; }
.announcement-img { width:240px; border-radius:10px; display:block; box-shadow:0 3px 8px rgba(0,0,0,0.06); }
.announcement-hr { width:60%; max-width:360px; margin:8px auto; border:none; border-top:1px solid rgba(160,160,160,0.25); }


/* Highlighted content box */
.highlight-box {
  border: 2px solid rgba(11, 60, 93, 0.15);
  background: rgba(255,255,255,0.98);
}

/* Scholarship list */
.scholarship-list {
  margin: 14px 0 18px;
  padding-left: 22px;
}

.scholarship-list li {
  margin-bottom: 10px;
  font-size: 1.05em;
}

/* Badges */
.badge {
  display: inline-block;
  font-size: 0.75em;
  font-weight: 600;
  padding: 3px 8px;
  border-radius: 12px;
  margin-right: 8px;
  vertical-align: middle;
}

.badge-eu {
  background: #1f7a8c;
  color: #fff;
}

.badge-national {
  background: #0b3c5d;
  color: #fff;
}

.badge-international {
  background: #e6f0ff;
  color: #0b3c5d;
}

/* Buttons */
.btn-outline {
  padding:8px 14px; border:2px solid var(--accent); border-radius:8px;
  color:var(--accent); font-weight:400; text-decoration:none; display:inline-block;
  transition:0.18s;
}
.btn-outline:hover { background:var(--accent); color:#fff!important; transform:translateY(-2px); }

/* Contact grid */
.contact-grid { display:grid; grid-template-columns:1fr 1fr; gap:18px; margin-top:12px; }
.contact-card { border:1px solid rgba(200,200,200,0.5); padding:16px; border-radius:10px; box-shadow:var(--card-shadow); background:rgba(255,255,255,0.03); }
.contact-card h4 { color:var(--accent); margin-top:0; font-weight:400; }
.contact-img { width:85%; border-radius:10px; margin-top:10px; display:block; }

.centered-hr { width:420px; max-width:90%; margin:30px auto; border:none; border-top:2px solid #aaa; }

/* Project list */
.project-list { list-style:none; padding-left:0; margin:0; }
.project-list li { padding:16px 0; border-bottom:1px solid rgba(0,0,0,0.08); }
.project-list li:last-child { border-bottom:none; }
.project-title { margin:4px 0 6px; }

/* Responsive */
@media (max-width:900px) {
  .profile-container { flex-direction:column; text-align:center; }
  .announcement-item { flex-direction:column; text-align:center; gap:12px; }
  .announcement-img { width:100%; max-width:240px; flex:none; }
  .contact-grid { grid-template-columns:1fr; }
}
@media (max-width:480px) {
  .highlight { font-size:0.95rem; }
  .announcement-item { padding:10px; }
}
body { overflow-x:hidden; }
</style>
