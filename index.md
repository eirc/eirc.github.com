---
layout: page
title: The Blog
tagline: Supporting endangered taglines
---
{% include JB/setup %}

<!-- Add random posts when I know how

## Sample Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
-->

## To-Do

Read more of this blog

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## Don't forget to

<pre>
<code class="prompt">sudo rm -rf /</code>
</pre>
