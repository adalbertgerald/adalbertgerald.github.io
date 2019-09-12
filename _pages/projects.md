---
layout: page
title: projects
permalink: /projects/
description: List of projects I am currently working on.
order: 2
---
<table>
{% for project in site.projects %}
<tr>
<td><img src="{{project.img}}" alt="Project image" border="3"/></td>
<td><b>{{project.title}}</b>: {{project.description}}</td>
</tr>
{% endfor %}
</table>

NOTE: This page is under construction. Check back after sometime for more recent projects.
