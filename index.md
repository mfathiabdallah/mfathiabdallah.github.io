---
layout: default
title: About Me
---

<!-- Profile picture -->
<img class="ProfilePic" src="/assets/images/Me.jpg">

<!-- Profile address -->
<p class="ProfileAddress">Address: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed euismod ultrices mauris, ac gravida leo auctor ac. Pellentesque ut eleifend nulla. Fusce ut elit et est bibendum pharetra.</p>

<!-- Short Bio -->
<h2>Short Bio (last update: March 2023)</h2>
<p>Researcher in Food Toxicology Postdoctoral mandate of the <a href="https://www.ugent.be/nl/onderzoek/financiering/bof/postdoc/overzicht.htm" target="_blank" rel="noopener">Ghent University-Special Research Fund</a> (BOF).</p>
<p>I am a post-doctoral researcher in Toxicology field at <a href="https://www.ugent.be/en" target="_blank" rel="noopener">Ghent University</a>. My research spans from detection of natural toxins, such as mycotoxins and cyanobacterial toxins, in food and water through to the application of -Omics approach to understand the effect of a mixture of toxins and other environmental contaminants as micro- and nanoplastics on humans.</p>


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

