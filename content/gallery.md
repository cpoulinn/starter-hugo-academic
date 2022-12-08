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

<meta name="twitter:card" content="player"/>
<meta name="twitter:site" content="modelviewer"/>
<meta name="twitter:player:width" content="480"/>
<meta name="twitter:player:height" content="480"/>
<meta name="twitter:player" content="https://modelviewer.dev/examples/twitter/player.html?src=https://modelviewer.dev/shared-assets/models/NeilArmstrong.glb&poster=https://modelviewer.dev/shared-assets/models/NeilArmstrongPoster.webp&alt=Neil%20Armstrong%27s%20Spacesuit%20from%20the%20Smithsonian%20Digitization%20Programs%20Office%20and%20National%20Air%20and%20Space%20Museum&environmentImage=https%3A%2F%2Fmodelviewer.dev%2Fshared-assets%2Fenvironments%2Fmoon_1k.hdr"/>
<meta property="og:title" content="3D model-viewer embed"/>
<meta property="og:description" content="Neil Armstrong's Spacesuit from the Smithsonian Digitization Programs Office and National Air and Space Museum"/>
<meta property="og:image" content="https://modelviewer.dev/shared-assets/models/NeilArmstrong.png"/>

<meta http-equiv="refresh" content="0; url='https://modelviewer.dev/'"/>
