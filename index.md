---
layout: page
title: Welcome to Mash The Web!
tagline: Web Blogs of Mashups!
---
{% include JB/setup %}

Welcome to my web blog constructed using Github. It contains a list of website links. So far, it will include posts from 2020 to now (in 2025)!

## Some web stuff I have done in 2023

<p>
Mash The Web .NET Blog Website <a href="https://mashtheweb.azurewebsites.net/">here</a>
</p>

## Some web stuff I have done in 2020

<p>
Mash The Music Blog See <a href="http://mashthemusic.github.io/">here</a>
</p>

<p>
Mash The Music Blog See <a href="http://mashtheweb.wordpress.com/">here</a>
</p>


## Some websites I have done in 2020

<p>
  Affiliates BMA Website on
  <a href="https://affiliate.bma.org.uk">here</a>
</p>

<p>
  Real Estate PM See <a href="htpp://www.realestatepm.net">here</a>
</p>

## Some stuff I have done in 2016

<p>
Cultivate London See <a href="http://cultivatelondongfn.tumblr.com">here</a> 
</p>
<p>
Great War Essex. See <a href="http://mashtheweb.github.io/greatwaressex.html">here</a>
</p>

## Some Posts

This blog contains some posts.

Here's the "posts".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


