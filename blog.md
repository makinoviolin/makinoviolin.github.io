---
layout: page
title: ブログ
hero: /assets/img/speech-1080.jpg
---

<ul>
    {% for post in site.posts %}
      <li>
        <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
        {{ post.excerpt }}
      </li>
    {% endfor %}
  </ul>