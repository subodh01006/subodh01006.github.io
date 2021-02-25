---
layout: page
permalink: /talks/
title: Talks
description: Talks
years: [2020, 2019, 2018, 2017, 2016, 2015, 2014, 2013]
nav: true
profile:
  align: right
  image: prof_pic.jpg
---

<style >
.year{
color: #4b4b4b;
font-size: 30px;
border-bottom: 1px solid #ccc;
margin: 0 0 30px 0;
padding: 20px 0;
text-align: left;
font-family: "Lato", Helvetica, Arial, sans-serif;
font-weight: 300;
}

</style>
<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f talks -q @*[year={{y}}]* %}
{% endfor %}

</div>

