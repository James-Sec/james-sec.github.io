---
title: James-Sec
description: James-Sec collection of projects and blogs.
layout: default
---

# About Us
A two-person team consisting of [Joao Andreotti][github-io-joaoandreotti] and [Jorge Correia][ufpr-jorge-correia]

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> » <a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


[github-io-joaoandreotti]: <https://joaoandreotti.github.io> "joaoandreotti github"
[ufpr-jorge-correia]: <https://www.inf.ufpr.br/jpcorreia> "jorge-correia UFPR page"
