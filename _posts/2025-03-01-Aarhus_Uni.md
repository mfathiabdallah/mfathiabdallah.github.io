---
layout: post
title: "New position at Food Science Department, Aarhus University"
date: 2025-03-01
mathjax: true
inline: true
categories: media
canonical: https://www.mfathiabdallah.com/Aarhus_Uni/
---

<link rel="canonical" href="https://www.mfathiabdallah.com/Aarhus_Uni/">

<meta name="Career" content="New position at Food Science Department, Aarhus University">

<script type="application/ld+json">
{
  "@context": "http://schema.org",
  "@type": "Article",
  "headline": "New position at Food Science Department, Aarhus University",
  "datePublished": "2025-03-01",
  "description": "New position at Food Science Department, Aarhus University",
  "mainEntityOfPage": {
    "@type": "WebPage",
    "@id": "https://www.mfathiabdallah.com/Aarhus_Uni/"
  }
}
</script>

## Career

<div class="career-announcement">
  <div class="career-text">
    <p>
      I’m thrilled to share that I will be joining the Department of Food Science at Aarhus University, Denmark, as a Tenure Track Assistant Professor in Food Toxicology, starting April 1st, 2025.
    </p>

    <p>
      In this new role, I will focus on research into the evaluation of toxic compounds in novel and alternative food products and the development of innovative analytical methods—while bridging science with EU legislation and regulatory frameworks. I’m especially excited to contribute to building a dynamic research group within the Food Chemistry Science Team.
    </p>

    <p>
      This is a fantastic opportunity to deepen my work in food toxicology, mentor the next generation of scientists, and contribute to a vibrant international research community.
    </p>

    <p>
      Looking forward to this exciting journey and the opportunities ahead at Aarhus University!
    </p>
  </div>

  <div class="career-profile">
    <img
      class="profile-pic"
      src="/mohamed_fathi_abdallah_2023(2).jpg"
      alt="Mohamed Fathi Abdallah"
      onclick="openModal(this.src)"
    >
  </div>
</div>

<div class="career-banner">
  <img
    class="au-image"
    src="/images/AarhusUni.jpg"
    alt="Aarhus University"
    onclick="openModal(this.src)"
  >
</div>

<div id="imageModal" class="modal">
  <span class="close" onclick="closeModal()">&times;</span>
  <img class="modal-content" id="modalImage" alt="Expanded image">
</div>

<script>
function openModal(imgSrc) {
  var modal = document.getElementById("imageModal");
  var modalImg = document.getElementById("modalImage");
  modal.style.display = "block";
  modalImg.src = imgSrc;
}

function closeModal() {
  document.getElementById("imageModal").style.display = "none";
}

window.onclick = function(event) {
  var modal = document.getElementById("imageModal");
  if (event.target === modal) {
    modal.style.display = "none";
  }
}
</script>

<style>
/* Main announcement layout */
.career-announcement {
  display: flex;
  align-items: flex-start;
  justify-content: space-between;
  gap: 24px;
  margin: 24px 0;
}

.career-text {
  flex: 1;
}

.career-text p {
  margin-bottom: 16px;
  line-height: 1.7;
}

.career-profile {
  flex: 0 0 180px;
  text-align: right;
}

.profile-pic {
  width: 160px;
  max-width: 100%;
  height: auto;
  border-radius: 12px;
  cursor: pointer;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.18);
}

/* University image below */
.career-banner {
  margin-top: 24px;
  text-align: center;
}

.au-image {
  max-width: 100%;
  width: 700px;
  height: auto;
  border-radius: 12px;
  cursor: pointer;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.18);
}

/* Modal */
.modal {
  display: none;
  position: fixed;
  z-index: 9999;
  padding-top: 50px;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  overflow: auto;
  background-color: rgba(0, 0, 0, 0.9);
}

.modal-content {
  margin: auto;
  display: block;
  width: 80%;
  max-width: 700px;
}

.close {
  position: absolute;
  top: 15px;
  right: 35px;
  color: #fff;
  font-size: 40px;
  font-weight: bold;
  cursor: pointer;
}

.close:hover,
.close:focus {
  color: #bbb;
}

/* Mobile responsive */
@media (max-width: 768px) {
  .career-announcement {
    flex-direction: column-reverse;
    align-items: center;
  }

  .career-profile {
    text-align: center;
    flex: 0 0 auto;
  }

  .profile-pic {
    width: 130px;
  }

  .career-text {
    width: 100%;
  }
}
</style>
