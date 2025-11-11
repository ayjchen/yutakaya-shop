---
layout: splash
title: "豐家本舖"
lang: "zh-tw"
permalink: /zh-tw/

header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/outside4.jpg
  actions:
    - label: "地圖．聯絡我們"
      url: "/zh-tw/contact/"
excerpt: "豐家本舖是四國旅遊者與遍路行者在地的好朋友。<br>遊途中的您可在這裏暫歇片刻，喝杯茶、吹吹風、聊聊天，再繼續您精彩的行程！"
# intro: 
#   - excerpt: 'Nullam suscipit et nam, tellus velit pellentesque at malesuada, enim eaque. Quis nulla, netus tempor in diam gravida tincidunt, *proin faucibus* voluptate felis id sollicitudin. Centered with `type="center"`'
feature_row:
  - image_path: assets/images/flower.jpg
    # image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
    # alt: "placeholder image 1"
    # title: "Placeholder 1"
    # excerpt: "This is some sample content that goes here with **Markdown** formatting."
  - image_path: /assets/images/lanturn.jpg
    # alt: "placeholder image 2"
    # title: "Placeholder 2"
    # excerpt: "This is some sample content that goes here with **Markdown** formatting."
    # url: "#test-link"
    # btn_label: "Read More"
    # btn_class: "btn--primary"
  - image_path: /assets/images/manekineko.jpg
    # title: "Placeholder 3"
    # excerpt: "This is some sample content that goes here with **Markdown** formatting."
feature_row2:
  - image_path: /assets/images/products.jpg
    alt: "placeholder image 2"
    title: "土產商品小舖"
    excerpt: '商品店舖內備有精選的日本各地的優質暢銷商品、伴手禮、特色土產及各種精緻小物可供選購，滿足您旅途中發現及享受日本好物的需求。'
    url: "https://forms.gle/THaJU4U2S9F95mHK7"
    url_target: "_blank"
    btn_label: "前往訂單"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/plaza1.jpg
    alt: "placeholder image 2"
    title: "愜意休憩區"
    excerpt: '豐家本舖可供旅行者與遍路者在高松市的暫歇場所，在店舖營業時間內招待免費茶水及小點心（每人限一份、內容物由本店配置）。<br><br>在夏季，您可以暫避高溫歇歇腳，並喝一杯冰涼茶水。<br>在冬季，您也可以暫時小歇，喝杯溫熱的茶水再繼續精彩豐富的行程。'
    # url: "#test-link"
    # btn_label: "Read More"
    # btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/outside2.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Center Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

<!-- {% include feature_row id="feature_row4" type="center" %} -->

<div class="feature-row2-wrapper">
  {% include feature_row id="feature_row2" type="left" %}
</div>

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row %}