---
layout: default
title: Home
nav_order: 1
description: "Welcome"
---

# Welcome to The RBC Documentation

If you'd like to contribute to the development of this site, please see [this page](/docs/Contributing/contributing.md). Submit an issue or [Pull Request](https://github.com/PennLINC/RBC-Documentation/pulls), so it can be reviewed and added to the site.

#### Thank you to the contributors!
<ul class="list-style-none">
{% for contributor in site.github.contributors %}
  <li class="d-inline-block mr-1">
     <a href="{{ contributor.html_url }}"><img src="{{ contributor.avatar_url }}" width="32" height="32" alt="{{ contributor.login }}"/></a>
  </li>
{% endfor %}
</ul>


This documentation website was created using [Jekyll and Github pages](https://help.github.com/en/github/working-with-github-pages/setting-up-a-github-pages-site-with-jekyll); the template is [`just-the-docs`](https://pmarsceill.github.io/just-the-docs/).
