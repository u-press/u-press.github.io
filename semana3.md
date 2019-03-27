
---
layout: default
title: "Semana 3"
---
<div class="introduction">
<p> </p>
</div>
<b>Figura 1. Tabla de Requerimientos </b>
 <img src="http://i67.tinypic.com/152bxup.jpg" alt="Italian Trulli">
<hr>

<div class="toc">
  <h2>sample texts</h2>
  <ul class="texts">
  {% for item in site.texts %}
  
    <li class="text-title">
      <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
      </a>
    </li>
  {% endfor %}
  </ul>
</div>

