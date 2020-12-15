---
layout: page
title: projects
permalink: /projects/
description:
order: 4
---
<table>
{% for project in site.projects %}
<tr>
<td><img src="{{project.img}}" alt="Project image" border="3"/></td>
<td><b>{{project.title}}</b>: {{project.description}}</td>
</tr>
{% endfor %}
</table>

