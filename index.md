---
layout: page
tagline: Supporting tagline
---
{% include JB/setup %}

## Dernières news

<ul class="posts">
  {% for post in site.posts %}

    {% if forloop.index == 5 %}
        {% break %}
    {% endif %}    

    <li><span><strong>[{{ post.date | date_to_string }}]</strong></span> <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a>: {{ post.content | split:'<!-- more -->' | first | replace:'<p>', '' | append:'…' }}</li>
  {% endfor %}
</ul>

{% include themes/perfug/index.html %}