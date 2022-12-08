---
layout: default
title: Nosh Bagel
desc: Hand-rolled naturally leavened bagels made in Asheville, NC
slug: home
---

<h1 class="visually-hidden">{{ site.title }}</h1>
<p class="visually-hidden">{{ site.description }}</p>

{% include svg/logo-wordmark.html class="logo-wordmark" %}
{% include svg/bagel-bialy.html class="tagline" %}

<ul class="desc">
	<li class="desc-item">{% include svg/schmears.html class="desc-item__svg" %}</li>
	<li class="desc-item">{% include svg/sandwiches.html class="desc-item__svg" %}</li>
	<li class="desc-item">{% include svg/hand-shaped.html class="desc-item__svg" %}</li>
	<li class="desc-item">{% include svg/naturally-leavened.html class="desc-item__svg" %}</li>
</ul>

{% include svg/orders-inquiries.html class="orders-inquiries" %}
<div><a href="mailto:hello@noshavl.com">{% include svg/email.html class="email" %}</a></div>

{% include svg/logo-icon.html class="logo-icon" %}
