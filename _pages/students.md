---
layout: bio
permalink: /students/
title: Team
description: Current students and alumni
teams: [Manohar Kaul,Charu Sharma, Anson Simon Bastos, Akshita Parekh, Subodh Nigam, Vishal Singh Yadav, Jatin Chauhan, Deepak Nathani, Nikhil P. Kumaar, Pratik Shukla, Varun Mishra]
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
<div class="resources">

{% for name in page.teams %}
  <h2 class="year">{{name}}</h2>
  {% bibliography -f resources -q @*[full_name={{name}}]*  %}
{% endfor %}

</div>
