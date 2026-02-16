---
layout: splash
title: "豊家本舗"
lang: "ja"
permalink: /ja/

header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/outside4.jpg
  actions:
    - label: "地図・お問い合わせ"
      url: "/ja/contact/"
excerpt: "豊家本舗は四国を旅する旅行者やお遍路さんの心強い味方です。<br>旅の途中にちょっと立ち寄って、お茶を飲んだり、風にあたったり、おしゃべりをして、次の素敵な行程へ向けてひと息ついてください。"

feature_row:
  - image_path: assets/images/flower.jpg
  - image_path: /assets/images/lanturn.jpg
  - image_path: /assets/images/manekineko.jpg

feature_row2:
  - image_path: /assets/images/products.jpg
    alt: "placeholder image 2"
    title: "土産物ショップ"
    excerpt: '店内に当店では、日本各地から厳選した人気の高い高品質な商品を取り揃えており、定番のお土産や地域限定の特産品、さまざまな可愛らしい雑貨をご購入いただけます。旅の途中で、日本ならではの魅力を存分にお楽しみください。<br><br>また、お土産やお菓子類の販売に加え、話題の新商品である**焼きホタテソーセージ**、**焼きたての和風もち**、**熱々のおでん**、そして各種ドリンクなど、出来たての軽食もご用意しております。ぜひその場でお買い求めいただき、ご賞味ください。は日本各地から厳選した人気商品、ギフト、特産品、そしてさまざまな可愛い小物をご用意しております。旅の途中で見つける日本の「良いもの」をぜひお楽しみください。'
    # url: "https://forms.gle/THaJU4U2S9F95mHK7"
    # url_target: "_blank"
    # btn_label: "注文ページへ"
    # btn_class: "btn--primary"

feature_row3:
  - image_path: /assets/images/plaza1.jpg
    alt: "placeholder image 2"
    title: "くつろぎ休憩スペース"
    excerpt: '豊家本舗は高松市で旅行者やお遍路さんがひと息つける休憩スポットです。営業時間内は無料のお茶とお菓子（お一人様一セット、内容は当店指定）をご提供しています。<br><br>夏は涼しい店内で冷たいお茶をどうぞ。<br>冬は温かいお茶で体を温め、次の旅路へ備えてください。'

feature_row4:
  - image_path: /assets/images/outside2.jpg
    alt: "placeholder image 2"
    title: "中央揃えのサンプルイメージ"
    excerpt: 'これは **Markdown** 形式で記述されたサンプルコンテンツです。`type="center"` を使用して中央揃えにしています。'
    url: "#test-link"
    btn_label: "詳しく見る"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

<div class="feature-row2-wrapper">
  {% include feature_row id="feature_row2" type="left" %}
</div>

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row %}
