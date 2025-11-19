---
layout: single
title: "Contact Us"
lang: en
permalink: /en/contact/
---

<style>
  /* container height for the locator */
  .store-locator-wrapper {
    height: 60vh;
    min-height: 360px;
  }

  gmpx-store-locator {
    width: 100%;
    height: 100%;
  }
</style>

<div class="store-locator-wrapper">
  <!-- Replace YOUR_API_KEY_HERE with your real API key -->
  <gmpx-api-loader key="AIzaSyAEtGbfN6UY7aIVkZwY_N0bzFgYibPMBQg" solution-channel="GMP_QB_locatorplus_v11_c"></gmpx-api-loader>
  <gmpx-store-locator id="store-locator" map-id=""></gmpx-store-locator>
</div>

<script type="module">
  const CONFIGURATION = {
    locations: [
      {
        title: "Yutakaya",
        address1: "Kō-1867-1 Kokubunjichō Fuke",
        address2: "Takamatsu, Kagawa 769-0103, Japan",
        coords: { lat: 34.27405756057258, lng: 133.9710070977311 },
        placeId: "ChIJU-FZWxDDUzUR6hdkWz_YMro"
      }
    ],
    mapOptions: {
      center: { lat: 34.27406, lng: 133.97101 },
      zoom: 12,
      fullscreenControl: true,
      mapTypeControl: false,
      streetViewControl: false,
      zoomControl: true,
      maxZoom: 17,
      mapId: ""
    },
    mapsApiKey: "AIzaSyAEtGbfN6UY7aIVkZwY_N0bzFgYibPMBQg",
    capabilities: { input:false, autocomplete:false, directions:false, distanceMatrix:false, details:false, actions:false }
  };

  (async () => {
    // load the extended component library and configure the locator
    await import('https://ajax.googleapis.com/ajax/libs/@googlemaps/extended-component-library/0.6.11/index.min.js');
    await customElements.whenDefined('gmpx-store-locator');
    const locator = document.getElementById('store-locator') || document.querySelector('gmpx-store-locator');
    if (locator && locator.configureFromQuickBuilder) {
      locator.configureFromQuickBuilder(CONFIGURATION);
    } else {
      console.warn('gmpx-store-locator not available yet.');
    }
  })();
</script>

<br><br>
<div class="contact-info">
    <p><strong>Phone: </strong>080-8128-8973</p>
    <p><strong>Email: </strong><a href="mailto:yutakaya.contact@gmail.com">yutakaya.contact@gmail.com</a></p>
</div>
