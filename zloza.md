---
layout: page
title: Pierwiastki

---
<ul>
{% for item in site.data.zloza %}
  <li style="{% if item.czynna %}color: green {% endif %}">
  {{ item.name }} <em> {{item.zasoby}}</em>
  </li>
{% endfor %}
</ul>
