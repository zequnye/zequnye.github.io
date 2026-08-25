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
  .social .contact-icons {
    display: inline-flex !important;
    align-items: center !important;
    justify-content: center !important;
    gap: 1.2rem !important;
  }

  .social a {
    display: inline-flex !important;
    align-items: center !important;
    justify-content: center !important;
    text-decoration: none !important;
  }

  .social a.orcid-icon i {
    color: #a6ce39 !important;
    font-size: 2.2rem !important;
  }

  .post-header {
    margin-bottom: 0px !important;
    padding-bottom: 0px !important;
  }
  
  .post article, .post-content {
    margin-top: -10px !important;
  }

  .post .profile {
    margin-top: -3.2rem !important;
    margin-bottom: 0px !important;
  }

  .post .profile img {
    max-height: 230px !important;
    width: auto !important;
    object-fit: cover;
  }

  .post-content p {
    margin-bottom: 8px !important;
  }
  .post-content ul {
    margin-bottom: 12px !important;
  }
  .social {
    padding-top: 0px !important;
    margin-top: 10px !important;
  }
</style>

<script>
  document.addEventListener("DOMContentLoaded", function() {
    var titleEl = document.querySelector('.post-title');
    if (titleEl) {
      titleEl.innerHTML = 'Zequn <span class="font-weight-bold">YE</span>';
    }

    var contactIcons = document.querySelector('.social .contact-icons') || document.querySelector('.social');
    if (contactIcons && !document.querySelector('.orcid-icon')) {
      var orcidA = document.createElement('a');
      orcidA.className = 'orcid-icon';
      orcidA.href = 'https://orcid.org/0009-0002-7068-0366';
      orcidA.target = '_blank';
      orcidA.title = 'ORCID';
      orcidA.innerHTML = '<i class="fa-brands fa-orcid"></i>';
      contactIcons.appendChild(orcidA);
    }

    setTimeout(function() {
      document.querySelectorAll('a[href*="cv"]').forEach(function(el) {
        el.setAttribute('title', 'CV');
        el.setAttribute('data-original-title', 'CV');
      });
      document.querySelectorAll('a[href*="scholar.google"]').forEach(function(el) {
        el.setAttribute('title', 'Google Scholar');
        el.setAttribute('data-original-title', 'Google Scholar');
      });
    }, 200);
  });
</script>