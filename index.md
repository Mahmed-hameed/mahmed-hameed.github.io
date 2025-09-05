---
layout: splash
title: "Portfolio"
excerpt: ""
header:
  overlay_color: "#000"
  overlay_filter: "0.4"
  overlay_image: /assets/site/hero.jpg
  cta_label: "Browse Projects"
  cta_url: "/projects/"
  caption: ""
intro:
  - excerpt: ""
feature_row:
  - image_path: /assets/site/feature-it.png
    alt: "IT Projects"
    title: "IT Projects"
    excerpt: "Web apps • automation • tooling"
    url: "/projects/it/"
    btn_label: "Explore IT"
    btn_class: "btn--primary"
  - image_path: /assets/site/feature-cyber.png
    alt: "Cyber Security"
    title: "Cyber Security"
    excerpt: "Labs • write-ups • research"
    url: "/projects/cyber/"
    btn_label: "Explore Cyber"
    btn_class: "btn--primary"
  - image_path: /assets/site/feature-about.png
    alt: "About"
    title: "About"
    excerpt: "Background • skills • goals"
    url: "/about/"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}
{% include feature_row %}
