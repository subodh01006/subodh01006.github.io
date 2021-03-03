---
layout: page
permalink: /teaching/
title: Teaching
description: Teaching
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
<!-- <div class="slp__liveNotStarted" data-slp-target="liveThumbnail" style="background-image: url(&quot;https://d2ygwrecguqg66.cloudfront.net/data/presentations/38938281/slideslive_charu-sharma_deepak-nathani_manohar-kaul_solving-partial-assignment-problems-using-random-simplicial-complexes.jpg?1606758741&quot;);">
    <div class="slp__liveNotStartedTitle__gradient"></div>
    <div class="slp__liveNotStartedTitle">
      <div class="slp__liveNotStartedTitle__logo"></div>
      <div class="slp__liveNotStartedTitle__text" data-slp-localized="liveStartSoon">Livestream will start soon!</div>
    </div>
  </div>
   -->
<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f teaching -q @*[year={{}}]* %}
{% endfor %}

</div>

