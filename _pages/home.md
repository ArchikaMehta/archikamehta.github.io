---
layout: splash
permalink: /
hidden: true
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/header.png
  #actions:
   # - label: "<i class='fas fa-download'></i> Install now"
   #   url: "/docs/quick-start-guide/"
excerpt: >
  “Quality is never an accident; it is always the result of intelligent effort.” – John Ruskin.<br />
feature_row:
  - image_path: /assets/images/ApplicationLayersTeaser.png
    alt: "ApplicationLayersTeaser"
    title: "Different layers in a Software"
    excerpt: "Often known as tiered architecture, or n-tier architecture, a multi layered software architecture consists of ..."
    url: "/software-layers/"
    btn_class: "btn--primary"
    btn_label: "Learn more"
  - image_path: /assets/images/SoftwareDevelopmentTeaser.jpg
    alt: "SoftwareDevelopmentTeaser"
    title: "How does a software get developed"
    excerpt: "First let's understand why a software is developed. The software can be developed for a variety of purposes..."
    url: "/software-development/"
    btn_class: "btn--primary"
    btn_label: "Learn more"
  - image_path: /assets/images/SDLC_Teaser.jpg
    alt: "100% free"
    title: "SDLC - Software Development Life Cycle"
    excerpt: "SDLC is a process used by the software industry to design, develop and test high quality software..."
    url: "/sdlc/"
    btn_class: "btn--primary"
    btn_label: "Learn more"      
---

{% include feature_row %}

<div class="grid__wrapper">
  {% for post in site.posts limit:4 %}
    {% include archive-grid.html type="grid" %}
  {% endfor %}
</div>