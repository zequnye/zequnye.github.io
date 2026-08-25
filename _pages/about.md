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
  .social img, .social svg {
    height: 1.8rem !important;
    width: auto !important;
    vertical-align: sub !important;
    margin-bottom: 0px !important;
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

    document.querySelectorAll('.post-title .badge, .post-header .badge, .post-title a, .post-header a').forEach(function(el) {
      if (el.classList.contains('badge') || (el.getAttribute('href') && el.getAttribute('href').includes('orcid'))) {
        el.remove();
      }
    });

    setTimeout(function() {
      document.querySelectorAll('a[href*="cv"]').forEach(function(el) {
        el.setAttribute('title', 'CV');
        el.setAttribute('data-original-title', 'CV');
        if (window.jQuery && $(el).data('bs.tooltip')) {
          $(el).attr('data-original-title', 'CV').tooltip('update');
        }
      });

      document.querySelectorAll('a[href*="scholar.google"]').forEach(function(el) {
        el.setAttribute('title', 'Google Scholar');
        el.setAttribute('data-original-title', 'Google Scholar');
        if (window.jQuery && $(el).data('bs.tooltip')) {
          $(el).attr('data-original-title', 'Google Scholar').tooltip('update');
        }
      });
    }, 200);
  });
</script>