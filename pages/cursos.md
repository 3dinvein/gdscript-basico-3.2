---
layout: page
title: Cursos
permalink: /cursos/
tags: [Cursos, Aulas]
---

<div class="container">
  <div class="row pt-5 m-auto">
    {% for curso in site.data.cursos %}
    <div class="col-md-6 col-lg-4 pb-3">{% include card.html curso=curso %}</div>
    {% endfor %}
  </div>
</div>