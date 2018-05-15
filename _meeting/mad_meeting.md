---
title: Schedule
layout: page
weight: 1
---

<h1>Meeting Schedule and Links</h1>
<h2>May 17, 2018</h2>

{% assign dayone = site.data.agenda | where: "date", "2018-05-17" %}

{% assign daytwo = site.data.agenda | where: "date", "2018-05-18" %}

{% for times in dayone %}
<div class="floating-box">
	<div class="bio">
	<strong>{{times.timestart}}</strong> - <em class="part-name">{{times.title}}</em><br>
	<p>{{times.description}}</p>
	</div>
	<div class="photo">
		{% if times.image %}
		<img src="../{{times.image}}" height="50px" align="right" style="padding:7px 0 0 0px;">
		{% endif %}
	</div>
</div>
{% endfor %}
<br>
<h2>May 18, 2018</h2>

{% for times in daytwo %}
<div class="floating-box">
	<div class="bio">
	<strong>{{times.timestart}}</strong> - <em class="part-name">{{times.title}}</em><br>
	<p>{{times.description}}</p>
	</div>
	<div class="photo">
		{% if times.image %}
		<img src="../{{times.image}}" height="50px" align="right" style="padding:7px 0 0 0px;">
		{% endif %}
	</div>
</div>
{% endfor %}
