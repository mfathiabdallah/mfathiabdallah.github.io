---
layout: page
sitemap:
  lastmod: 2023-04-10
  exclude: 'no'
---

<!--
<div class="alert">
  <span style="display: inline-block; text-align: center;">
    For the intended experience,<br>please use Google Chrome.
  </span>
  <button class="closebtn" onclick="this.parentElement.style.display='none';">Close</button>
</div>
-->

<!-- Profile picture -->
<img class="ProfilePic" img width=150 img align="right" style="float: right; margin-left: 20px;" src="Me.jpg">

Short Bio (last update: April 2023)

Researcher in Food Toxicology Postdoctoral mandate of the <a href="https://www.ugent.be/nl/onderzoek/financiering/bof/postdoc/overzicht.htm" target="_blank" rel="noopener">Ghent University-Special Research Fund</a> (BOF).
I am a post-doctoral researcher in Toxicology field at <a href="https://www.ugent.be/en" target="_blank" rel="noopener">Ghent University</a>. My research spans from detection of natural toxins, such as mycotoxins and cyanobacterial toxins, in food and water through to the application of -Omics approach to understand the effect of a mixture of toxins and other environmental contaminantes as micro- and nanoplastics on humans.
<br /> <br />

I received my bachelor in Veterinary Medical Sciences from <a href="https://www.aun.edu.eg/main/" target="_blank" rel="noopener">Assiut University</a>, Egypt in 2011. After that, I joined the Pharmaceutical Toxicology Department, <a href="https://www.hacettepe.edu.tr/english" target="_blank" rel="noopener">Hacettepe University</a>, Turkey in September 2013 (through the <a href="https://www.turkiyeburslari.gov.tr/" target="_blank" rel="noopener">Türkiye Scholarships</a>) as a masters student and graduated in May 2016. During my masters, I was award an <a href="https://erasmus-plus.ec.europa.eu/" target="_blank" rel="noopener">Erasmus+</a> internship to join the Chemical Risks Group at <a href="https://www.ifado.de/ifadoen/" target="_blank" rel="noopener">IfADo</a> Institute in Dortmund, Germany. I conducted my master thesis on mycotoxin analysis through another <a href="https://erasmus-plus.ec.europa.eu/" target="_blank" rel="noopener">Erasmus+</a> exchange scholarship at the <a href="https://boku.ac.at/en/" target="_blank" rel="noopener">University of Natural Resources and Life Sciences, Vienna</a> (BOKU) in Tulln, Austria.

In August 2016, I joined the Centre of Excellence of Mycotoxicology & Public Health, <a href="https://www.ugent.be/en" target="_blank" rel="noopener">Ghent University</a>, Belgium for my PhD to work on the mitigation of toxigenic fungi and their mycotoxins. My PhD work was part of <a href="http://www.mycokey.eu/" target="_blank" rel="noopener">Mycokey</a> project which was funded by the EU Horizon 2020. I joined the Teagasc Food Research Centre in As


<!-- News and Twitter timeline -->
<div style="display: flex;">
  <div style="flex: 1; margin-right: 50px;">
    <h2>News</h2>
    <ul>
      {% for post in site.posts %}
      <li><span style="font-weight: bold;">{{ post.date | date: "%Y-%m-%d" }}</span> - <a href="{{ post.url }}">{{ post.title }}</a></li>
      {% endfor %}
    </ul>
  </div>
  <div style="width: 220px;">
    <a class="twitter-timeline"
       href="https://twitter.com/MoFathiAbdallah?ref_src=twsrc%5Etfw"
       data-tweet-limit="4"
       data-width="250"
       data-height="450"
       data-align="right">
      Tweets by MoFathiAbdallah
    </a>
    <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
  </div>
</div>

<!-- Announcement -->
<div>
  <h2>Announcements</h2>
  <hr />
  <div style="display: flex;">
    <div style="flex: 1; margin-right: 50px;">
      <h3 style="margin-bottom: 0;">01 December 2022</h3>
      <p style="margin-top: 0;">A new Special Issue in collaboration with Dr. Elisabeth Varga, Dr. Mohamed Fathi Abdallah, and Dr. Shupeng Yang 🤝</p>
      <p style="margin-top: 0;">"<a href="https://lnkd.in/g3-kW8dY" target="_blank" style="color:#ffefd5;">Current Research on Mycotoxins in Food and Feed: From Detection and Unravelling of Toxicity to Control</a>"</p>
      <p style="margin-top: 0;">See more information at: <a href="https://lnkd.in/g3-kW8dY" target="_blank">https://lnkd.in/g3-kW8dY</a></p>
      <p style="margin-top: 0;">#mycotoxins #toxicology #MDPI #open_access</p>
    </div>
    <div>
      <img src="/images/Special-issue-toxins.png" alt="Special issue" style="width: 450px;">
    </div>
  </div>
</div>

