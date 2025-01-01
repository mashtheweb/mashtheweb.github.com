---
layout: page
title: Welcome to Mash The Web!
tagline: Web Blog of Mashups!
---
{% include JB/setup %}

Welcome to my web blog constructed by Github. So far, it will include posts from 2020 to now!

## Some stuff I have done in 2023

<p>
Mash The Web .NET Blog Website <a href="https://mashtheweb.azurewebsites.net/">here</a>
</p>

## Some stuff I have done in 2020

<p>
Mash The Music Blog See <a href="http://mashthemusic.github.io/">here</a>
</p>

<p>
Mash The Music Blog See <a href="http://mashtheweb.wordpress.com/">here</a>
</p>

## Some websites I have done in 2020

<p>
  Real Estate PM See <a href="htpp://www.realestatepm.net"><here</a>
</p>

## Some stuff I have done in 2016

<p>
Cultivate London See <a href="http://cultivatelondongfn.tumblr.com">here</a> 
</p>
<p>
Great War Essex. See <a href="http://mashtheweb.github.io/greatwaressex.html">here</a>
</p>

## Some Posts

This blog contains some posts!

Here's the "posts".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


