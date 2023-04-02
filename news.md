---
layout: page
title: Biodiversity and Climate News
permalink: /news/
---

<h5>
Click and drag on the plot to zoom-in. Double-click to zoom-out. Click and drag the axis to pan along one axis. Double click on the legend to select a series. Single click on the legend to add series for comparison
</h5>



  {% include aggregate.html %}
 
<!-- Content for desktop devices -->
<h5 style="display:block;">
Click and drag on the plot to zoom-in. Double-click to zoom-out. Click and drag the axis to pan along one axis. Double click on the legend to select a series. Single click on the legend to add series for comparison
</h5>
<div class = >





<h2 style="display:block;">Desktop Content</h2>
<p style="display:block;">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>

<!-- Content for mobile devices -->
<h2 style="display:none;">Mobile Content</h2>
<p style="display:none;">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>

<!-- Only display mobile content on screens smaller than 600 pixels -->
<div id="mobile-content" style="display:none;">
  <h2>Mobile Content</h2>
  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
</div>

<script>
  if (window.innerWidth < 600) {
    document.getElementById("mobile-content").style.display = "block";
    document.querySelectorAll("[style*='display:block;']").forEach(function(el) {
      el.style.display = "none";
    });
  }
</script>
  
  
  

<head>
	<title>Responsive Block Example</title>
	<style>
		/* Styles for desktop devices */
		.desktop {
			display: block;
		}
		/* Styles for mobile devices */
		@media only screen and (max-width: 600px) {
			.mobile {
				display: block;
			}
			.desktop {
				display: none;
			}
		}
	</style>
</head>
<body>
	<div class="desktop">
		{% include desktop.md %}
	</div>
	<div class="mobile">
		{% include mobile.md %}
	</div>
</body>

  
  
  
