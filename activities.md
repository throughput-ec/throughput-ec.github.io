---
title: Activities
layout: page
weight: 1
permalink: "/activities/"
---

# Throughput Activities

<div class="bounder">

{% for meets in site.meeting %}
  <div class="col-lg-3 col-md-6 text-center">
    <div class="resource-box">
      <big>{{ meets.title }}</big> &#8226; <small>{{ meets.description }} [<a href="{{meets.url}}">Link</a>]</small><br><p></p>
    </div>
  </div>
{% endfor %}

</div>
