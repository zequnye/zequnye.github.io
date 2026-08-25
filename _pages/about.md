---
layout: about
title: about
permalink: /
subtitle: 

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false
  more_info: 

selected_papers: false
social: true

announcements:
  enabled: false

latest_posts:
  enabled: false
---

<div style="margin-top: 15px;">
  <p>Welcome to my personal homepage.</p>
  <p>I am a PhD Student in Graduate School of Economics, Nagoya University.</p>
  <p style="margin-top: 15px;">My research interests primarily include:</p>
  <ul>
    <li><strong>Dynamic Macroeconomics</strong></li>
    <li><strong>Search-and-Matching Theory</strong></li>
    <li><strong>Growth Theory</strong></li>
    <li><strong>Spatial Economics</strong></li>
  </ul>
</div>

<style>
  .post .profile {
    margin-top: -1.8rem !important;
    margin-bottom: 0px !important;
  }

  .post .profile img {
    max-height: 230px !important;
    width: auto !important;
    object-fit: cover;
  }

  .post-content .social,
  body .social:not(.custom-social) {
    display: none !important;
  }

  .custom-social {
    display: flex !important;
    justify-content: center !important;
    align-items: center !important;
    gap: 1.8rem !important;
    margin-top: 25px !important;
  }

  .custom-social a {
    color: var(--global-text-color) !important;
    font-size: 2.8rem !important;
    text-decoration: none !important;
    transition: opacity 0.2s ease;
    display: inline-flex !important;
    align-items: center !important;
    justify-content: center !important;
    line-height: 1 !important;
  }

  .custom-social a:hover {
    opacity: 0.7;
  }

  .custom-social a.cv-link i {
    font-size: 2.8rem !important;
  }

  .custom-social a.orcid-link i {
    color: #a6ce39 !important;
    font-size: 2.8rem !important;
  }
</style>

<div class="custom-social">
  <!-- CV -->
  <a href="{{ 'assets/pdf/CV20260825_Zequn YE.pdf' | relative_url }}" title="CV" class="cv-link" target="_blank">
    <i class="ai ai-cv"></i>
  </a>

  <!-- Email -->
  <a href="mailto:ye.zequn.h8@s.mail.nagoya-u.ac.jp" title="Email">
    <i class="fa-solid fa-envelope"></i>
  </a>

  <!-- Google Scholar -->
  <a href="https://scholar.google.com/citations?user=tHys6MUAAAAJ" title="Google Scholar" target="_blank">
    <i class="ai ai-google-scholar"></i>
  </a>

  <!-- ORCID -->
  <a href="https://orcid.org/0009-0002-7068-0366" title="ORCID" class="orcid-link" target="_blank">
    <i class="fa-brands fa-orcid"></i>
  </a>
</div>

<script>
  document.addEventListener("DOMContentLoaded", function() {
    var titleEl = document.querySelector('.post-title');
    if (titleEl) {
      titleEl.innerHTML = 'Zequn <span class="font-weight-bold">YE</span>';
    }
  });
</script>