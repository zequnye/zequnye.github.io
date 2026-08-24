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
  .post-header {
    display: flex !important;
    justify-content: space-between !important;
    align-items: flex-start !important;
    margin-bottom: 0px !important;
    padding-bottom: 0px !important;
  }
  
  .post article, .post-content {
    margin-top: -10px !important;
  }

  .post-header .profile {
    float: none !important;
    margin: 0 0 0 25px !important;
    width: auto !important;
    max-width: 40% !important;
  }

  .post-header .profile img {
    max-height: 235px !important;
    width: auto !important;
    object-fit: cover;
  }

  .post-header .more-info {
    font-size: 0.85rem !important;
    line-height: 1.35 !important;
    margin-top: 8px !important;
    text-align: center !important;
    color: #555;
  }

  .post-content p {
    margin-bottom: 8px !important;
  }
  .post-content ul {
    margin-bottom: 12px !important;
  }
  .social {
    padding-top: 0px !important;
    margin-top: 8px !important;
  }
</style>

<script>
  document.addEventListener("DOMContentLoaded", function() {
    var titleEl = document.querySelector('.post-title');
    if (titleEl) {
      titleEl.innerHTML = 'Zequn <span class="font-weight-bold">YE</span>';
    }

    var headerEl = document.querySelector('.post-header');
    var profileEl = document.querySelector('.profile');
    if (headerEl && profileEl) {
      headerEl.appendChild(profileEl);
    }
  });
</script>