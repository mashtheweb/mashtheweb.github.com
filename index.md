---
layout: page
title: Welcome to Mash The Web!
tagline: Web Blog of Mashups!
---
{% include JB/setup %}

Welcome to my simple web blog constructed by Github. So far, it will only some sample posts.

## Some stuff I have done this year

<p>
Cultivate London (to be continued) See http://cultivatelondongfn.tumblr.com
</p>
<p>
Great War Essex. See <a href="http://mashtheweb.github.io/greatwaressex.html">here</a>
</p>
## Some Posts

This blog contains some posts as a starter for some blog data.

Here's the sample "posts".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## To-Do

Get this blog up and running with more posts.


