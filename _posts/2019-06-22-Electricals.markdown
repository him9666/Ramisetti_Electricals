---
layout: "page"
title:  "Contact details for Electrical Services"
date:   2019-06-22 12:56:07 +0530
categories: jekyll update
author: Himesh
permalink: Services
---

<!-- {% for file in site.static_files %}
 {{ file.path }}
 {% if file.image %}
 <img src="image/thunder" alt="{file.name}">
 {% endif %}
{% endfor %}


<img src="images/thunder.jpg" >
<br/> -->
<img src="images/Electrical-Panel-Repairs.jpeg" >
<br/>

{% for person in site.data.people %}
{{ person.name }} , {{ person.role }}  {{ person.profile }} ,
<br/> {{ person.contact }}
{% endfor %}





