---
layout: page
title: Biodiversity and Climate News
permalink: /news/
---

 


<!-- Styles for desktop and mobile devices -->
<style>
	.desktop {
		display: block;
	}
	.mobile {
    		display: none;
  	}
	@media only screen and (max-width: 800px) {
		.mobile {
			display: block;
		}
		.desktop {
			display: none;
		}
	}
</style>

<div class="desktop">
	<h5>Click and drag on the plot to zoom-in. Double-click to zoom-out. Click and drag the axis to pan along one axis. Double click on the legend to select a series. Single click on the legend to add series for comparison</h5>
	 {% include aggregate.html %}
</div>

<!-- Content for mobile devices -->
<div class="mobile">
	<h2>Mobile Content</h2>
	<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
</div>
