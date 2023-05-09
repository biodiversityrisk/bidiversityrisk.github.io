---
layout: page
title: Spatial Exposures
permalink: /spatial/
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
 {% include map_risk_measures_county.html %}
<br>
</div>

<div class="desktop">
 {% include map_risk_measures_country.html %}
<br>
</div>

<!-- Content for mobile devices -->

<div class="mobile">
	
	<h5>For the best experience with our interactive figures, we recommend accessing our website using a desktop computer.</h5>
<br>
	 <img src="/image/map_risk_measures_county.png" alt="">
<br>
	<br>
 <img src="/image/map_risk_measures_country.png" alt="">
	<br>
</div>
