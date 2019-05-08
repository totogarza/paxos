---
layout: main
title: Bitácora
permalink: /bitacora/
---
<h4>
Bitácora:
</h4>

<table class="data-table">

    {% for post in site.categories.bitacora %}
    <tr>
        <td class='code date'>{{ post.date | date_to_string }} — </td>
        <td><a title='{{ post.title }}' href='{{ post.url }}'>{{ post.title}}</a></td>
    </tr>

    {% endfor %}
</table>