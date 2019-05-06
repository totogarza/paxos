---
layout: main
class: "post"
title: "Toto Garza"
---

<h4>
Entradas recientes:
</h4>
<ul class='big-list'>
    {% for post in site.categories.basic limit: 10 %}
        {% if post.url %}
        <li class="space-bottom"><span class="code">-</span><a title='{{post.date}}' href='{{ post.url }}'>{{ post.title }}</a></li>
        {% endif %}
    {% endfor %}

    
    {% if site.categories.basic.size > 10 %}
    <br>
    <li><em><a href='/archivo'>Hay {{ site.categories.basic.size | minus: 10}} más en el archivo…</a></em></li>
    {% endif %}

    {% if site.categories.basic.size < 11 %}
    <br>
    <li><em><a href='/archivo'>Ver todas las entradas.</a></em></li>
    {% endif %}

</ul>