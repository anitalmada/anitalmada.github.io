---
layout: default
title: Blog | Con Alma Tech
description: Artículos sobre tecnología, seguridad online, mantenimiento web y buenas prácticas digitales. Con Alma Tech - Buenos Aires.
permalink: /blog/
---

<div class="blog-page">
    <div class="container">
        <h1>Blog</h1>
        
        <div class="posts">
            {% for post in site.posts %}
                <article class="post">
                    {% if post.image %}
                        <div class="post-image">
                            <img src="{{ post.image | relative_url }}" alt="{{ post.title }}" loading="lazy">
                        </div>
                    {% endif %}
                    <h2 class="post-title"><a href="{{ post.url }}">{{ post.title }}</a></h2>
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
