---
layout: page
permalink: /projects/
title: Projects
years: [2020]
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
  <!-- <a href="/assets/img/greatfour.jpg" alt="Great four systems"></a> -->
  {% bibliography -f projects -q @*[year={{y}}]* %}
{% endfor %}

</div>