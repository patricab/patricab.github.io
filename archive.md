---
title: Archive
layout: page
order: 1
icon: fa-bars
---
<style>
    .container {
        display: flex;
        flex-wrap: wrap;
        justify-content: space-between;
    }

    .list {
        margin-left: 2em;
    }

    li {
        margin-left: 1em;
    }

</style>


<div class="container">
<ul class="category">
    <h3>Categories</h3>
    <br>
    <div class="list">
    {% for category in site.categories %}
    <h3>{{ category[0] }}</h3>
    <ul>
        {% for post in category[1] %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
        {% endfor %}
    </ul>
    {% endfor %}
    </div>
</ul>

<ul class="post">
    <h3>Most recent</h3>
    <br>
    <div class="list">
    {% for post in site.posts %}
    <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
    {% endfor %}
    </div>
</ul>
</div>

