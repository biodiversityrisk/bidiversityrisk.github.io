---
layout: page
title: Biodiversity and Climate News
permalink: /news/
---

<h5>
Click and drag on the plot to zoom-in. Double-click to zoom-out. Click and drag the axis to pan along one axis. Double click on the legend to select a series. Single click on the legend to add series for comparison
</h5>



<div class="desktop-only">
  This content is only visible on desktop.
 
</div>



<div style="display: block;">
  <!-- This content will always be displayed -->
  {% include aggregate.html %}
</div>

<div style="display: none;">
  <!-- This content will be hidden by default -->
  This content is only visible on mobile.
</div>

<!-- Apply the following styles to show or hide content based on screen size -->
<style>
  @media (max-width: 767px) {
    div[style="display: block;"] {
      display: none;
    }
    div[style="display: none;"] {
      display: block;
    }
  }
</style>
