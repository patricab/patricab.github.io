---
layout: post
title: DSKY
feature-img: "assets/img/thumbnails/dsky.jpg"
img: "assets/img/thumbnails/dsky.jpg"
tags: dsky
---
The DSKY/DSKYINO Project is a fork of the [Open DSKY Project](https://opendsky.com/)

This project aims to recreate a (almost) fully functional AGC/DSKY replica using Atmega328P processors (Arduino). The entire source code, and files for 3D-printing the case, will be open source and available on GitHub.

<ul>
  {% for post in site.tags.dsky %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
