---
layout: page
title: ""

---

<!-- Fellowships -->
<div class="collapsible">
  <h1 class="collapsible-title">&#10148; Fellowships</h1>
  <div class="collapsible-content">
    <ul>
      <li>(2020) Postdoctoral Fellowship-Special Research Fund Ghent University, <a href="https://www.ugent.be/en" target="_blank" rel="noopener">Ghent University</a> project, Belgium. Research grant number BOF20/PDO/032.</li>
      <li>(2020) Marie Curie Research Leaders 2025 - A Fellowship Programme developing the Next Generation of Agri-Food Research Leaders, Austria/Ireland (granted, but untaken/excused).</li>
      <li>(2016) PhD Research Fellowship, <a href="https://www.ugent.be/en" target="_blank" rel="noopener">Ghent University</a>, Belgium in the framework of <a href="http://www.mycokey.eu/" target="_blank" rel="noopener">Mycokey</a> project.</li>
      <li>(2015) Erasmus Student Mobility for Studies, Center for Analytical Chemistry, Universität für Bodenkultur Wien, Austria.</li>
      <li>(2014) Erasmus Student Mobility for Placement, _IfADo_ Institute, Dortmund, Germany.</li>
      <li>(2012) Turkish Government Scholarship, Turkey (through the <a href="https://www.turkiyeburslari.gov.tr/" target="_blank" rel="noopener">Türkiye Scholarships</a>).</li>
    </ul>
    <!-- Four images side by side -->
    <div class="image-container">
       <a href="https://www.turkiyeburslari.gov.tr/" target="_blank" rel="noopener"><img src="/images/moreaboutme/TurkishScholarship.jpeg" alt="TurkishScholarship"></a>
       <a href="https://erasmus-plus.ec.europa.eu/" target="_blank" rel="noopener"><img src="/images/moreaboutme/Erasmus2.jpg" alt="Erasmus"></a>
       <a href="http://www.mycokey.eu/" target="_blank" rel="noopener"><img src="/images/moreaboutme/Mycokey(3).png" alt="Mycokey"></a>
       <a href="https://tinyurl.com/mrfxhxaa" target="_blank" rel="noopener"><img src="/images/moreaboutme/UGENT2.png" alt="UGENT"></a>
    </div>  
  </div>
</div>

<!-- CSS for image container -->
<style>
  .image-container {
    display: flex;
    justify-content: center;
    align-items: center;
    margin-top: 20px;
  }
  
  .image-container img {
    width: 150px;
    height: 75px;
    margin: 5px;
    border: 1px solid #ddd;
    border-radius: 5px;
  }
</style>

 
<!-- Funds -->
<div class="collapsible">
  <h1 class="collapsible-title">&#10148; Funds</h1>
  <div class="collapsible-content">
    <ul>
      <li>(2021) <a href="https://www.ugent.be/en/research/funding/devcoop/globalmindsfund.htm" target="_blank" rel="noopener">VLIRUOS Global Minds Grant</a> from Ghent University for the project "AF-CYSTIN-milk" to assess the incidence of aflatoxin M1 and microcystin-LR in water buffalo milk from Philippines and their potential in vitro toxic interaction. Role: Principal Researcher.</li>
      <li>(2018) <a href="https://www.ugent.be/en/research/funding/devcoop/globalmindsfund.htm" target="_blank" rel="noopener">VLIRUOS Global Minds Grant</a> from Ghent University for the side project "MYCOSUGAR" to enrich our knowledge on mycotoxin occurrence in sugarcane as an important cash crop in Africa. Role: Principal Researcher.</li>
    </ul>
</div>
 
<!-- Scientific Awards -->
<div class="collapsible">
  <h1 class="collapsible-title">&#10148; Scientific Awards</h1>
  <div class="collapsible-content">
    <ul>
      <li>(2022) Best Oral Presentation from <a href="https://www.mdpi.com/journal/toxins" target="_blank" rel="noopener">Toxins journal</a> at the international conference <a href="http://pofmy.imi.hr/" target="_blank" rel="noopener">Power of Fungi and Mycotoxins in Climate Change Symposium</a>, which has been hold in Croatia.</li>
      <li>(2019) The Young Scientist Award during the <a href="https://eurachem2019.akki.ut.ee/" target="_blank" rel="noopener">EURACHEM 2019</a> meeting held in Tartu, Estonia.</li>
      <li>(2018) Best Poster Award from <a href="https://www.mdpi.com/journal/toxins" target="_blank" rel="noopener">Toxins journal</a> at the 2nd African Symposium on Mycotoxicology, which was hold in Kenya.</li>
    </ul>
</div>
 
<script>
  // Function to toggle collapsible sections
  function toggleCollapsible(event) {
    const content = event.target.nextElementSibling;
    event.target.classList.toggle("active");
    if (content.style.maxHeight){
      content.style.maxHeight = null;
    } else {
      content.style.maxHeight = content.scrollHeight + "px";
    }
  }

  // Add event listeners to collapsible titles
  const collapsibleTitles = document.getElementsByClassName("collapsible-title");
  for (let i = 0; i < collapsibleTitles.length; i++) {
    collapsibleTitles[i].addEventListener("click", toggleCollapsible);
  }
</script>

<style>
  /* Style for collapsible sections */
  .collapsible {
    border: 0px solid #ddd;
    margin-bottom: 0px;
    border-radius: 0px;
  }

  .collapsible-title {
    color: black; /* make font black */
    cursor: pointer;
    font-size: 18px;
    font-weight: bold;
    padding: 7.5px;
    border-radius: 0px;
    outline: none;
  }

  .collapsible-content {
    max-height: 0;
    overflow: hidden;
    transition: max-height 0.2s ease-out;
    padding: 0px;
  }

  .collapsible-title.active {
    background-color: #ccc;
  }
</style>
