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
