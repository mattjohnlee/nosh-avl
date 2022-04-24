---
layout: default
title: Nosh Bagel
desc: Hand-rolled naturally leavened bagels made in Asheville, NC
slug: home
---

<h1 class="visually-hidden">{{ site.title }}</h1>
<p class="visually-hidden">{{ site.description }}</p>

{% include svg/logo-wordmark.html class="logo-wordmark" %}
{% include svg/bagel-etc.html class="tagline" %}

<ul class="desc">
	<li class="desc-item">{% include svg/schmears.html class="desc-item__svg" %}</li>
	<li class="desc-item">{% include svg/sandwiches.html class="desc-item__svg" %}</li>
	<li class="desc-item">{% include svg/hand-rolled.html class="desc-item__svg" %}</li>
	<li class="desc-item">{% include svg/naturally-leavened.html class="desc-item__svg" %}</li>
</ul>

{% include svg/coming-soon.html class="coming-soon" %}
<div class="instagram-container">
	<a href="#" class="instagram-link">
		{% include svg/instagram.html class="instagram" %}	
	</a>
</div>
{% include svg/logo-icon.html class="logo-icon" %}
