---
# An instance of the Blank widget with a Gallery page element.
# Documentation: https://wowchemy.com/docs/getting-started/page-builder/
widget: blank

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 66

title: Gallery
subtitle:

design:
  columns: '1'

share: false
  
advanced:
  css_class: 'div.article-container {
  max-width: 1760px;
  padding: 0 20px;
  margin: 0 auto;
}'
---


<!-- Import the component -->
<script type="module" src="https://unpkg.com/@google/model-viewer/dist/model-viewer.min.js"></script>

<!-- Use it like any other HTML element -->
<model-viewer alt="Neil Armstrong's Spacesuit from the Smithsonian Digitization Programs Office and National Air and Space Museum" src="shared-assets/models/NeilArmstrong.glb" ar environment-image="shared-assets/environments/moon_1k.hdr" poster="shared-assets/models/NeilArmstrong.webp" shadow-intensity="1" camera-controls touch-action="pan-y"></model-viewer>

<iframe src="https://cpoulinn.github.io/AR-Demo/dino" height="500" width="100%" style="border:none;"></iframe>
