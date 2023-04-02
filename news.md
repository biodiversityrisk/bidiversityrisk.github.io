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
    
    <div class="desktop">
		  {% include aggregate.html %}
	</div>
	<div class="mobile">
		<p>hh</p>
	</div>
