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
    margin-bottom: 12px !important;
  }
  

  .post-header .profile {
    float: none !important;
    margin: 0 0 0 20px !important;
    width: auto !important;
  }

  .post-header .profile img {
    max-height: 220px !important;
    width: auto !important;
  }

  .post-header .more-info {
    font-size: 0.85rem !important;
    line-height: 1.3 !important;
    margin-top: 6px !important;
    text-align: center !important;
  }

  .post-content p, .post-content ul {
    margin-bottom: 8px !important;
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