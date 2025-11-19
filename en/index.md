---
layout: splash
title: "Yutakaya"
lang: "en"
permalink: /en/

header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/outside4.jpg
  actions:
    - label: "Map & Contact Us"
      url: "/en/contact/"
excerpt: "Yutakaya is a friendly stop for travelers and pilgrims exploring Shikoku.<br>Take a short break during your journey—enjoy a cup of tea, relax in the breeze, have a chat—and continue on your wonderful adventure refreshed!"

feature_row:
  - image_path: assets/images/flower.jpg
  - image_path: /assets/images/lanturn.jpg
  - image_path: /assets/images/manekineko.jpg

feature_row2:
  - image_path: /assets/images/products.jpg
    alt: "placeholder image 2"
    title: "Souvenir Shop"
    excerpt: 'Our shop offers a curated selection of popular items from across Japan, including gifts, regional specialties, and charming small goods—perfect for discovering delightful Japanese products during your travels.'
    url: "https://forms.gle/THaJU4U2S9F95mHK7"
    url_target: "_blank"
    btn_label: "Order Now"
    btn_class: "btn--primary"

feature_row3:
  - image_path: /assets/images/plaza1.jpg
    alt: "placeholder image 2"
    title: "Relaxation Area"
    excerpt: 'Yutakaya provides a cozy rest spot in Takamatsu for travelers and pilgrims. During business hours, we offer complimentary tea and a small snack (one set per person, contents selected by the shop).<br><br>In summer, cool down with a refreshing cup of iced tea.<br>In winter, warm up with a hot drink before continuing your journey.'
    
feature_row4:
  - image_path: /assets/images/outside2.jpg
    alt: "placeholder image 2"
    title: "Center-Aligned Placeholder Image"
    excerpt: 'This is sample content written with **Markdown** formatting. Centered using `type="center"`.'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

<div class="feature-row2-wrapper">
  {% include feature_row id="feature_row2" type="left" %}
</div>

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row %}
