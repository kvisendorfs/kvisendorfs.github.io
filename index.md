---
layout: default
---

<p>
  {% for post in site.posts %}
    <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>

    <div class="entry">
        {{ post.excerpt }}
    </div>

    <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a>
  {% endfor %}
</p>
