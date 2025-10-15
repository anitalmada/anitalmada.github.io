---
layout: default
title: Blog
permalink: /blog/
---

<div class="blog-page">
    <div class="container">
        <h1>Blog</h1>
        
        <div class="posts">
            {% for post in site.posts %}
                <article class="post">
                    <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
                    <p class="post-meta">{{ post.date | date: "%B %d, %Y" }}</p>
                    <div class="post-excerpt">
                        {{ post.excerpt | default: post.content | strip_html | truncate: 200 }}
                    </div>
                    <a href="{{ post.url }}" class="read-more">Leer más</a>
                </article>
            {% endfor %}
        </div>
    </div>
</div>
