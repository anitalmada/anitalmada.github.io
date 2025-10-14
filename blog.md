---
layout: default
title: Blog
permalink: /blog/
---

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

<style>
.container {
    max-width: 800px;
    margin: 0 auto;
    padding: 40px 20px;
}

.posts {
    margin-top: 40px;
}

.post {
    background: #FDFBF8;
    padding: 30px;
    margin-bottom: 30px;
    border-radius: 15px;
    box-shadow: 0 5px 20px rgba(58, 102, 58, 0.1);
}

.post h2 {
    color: #3A663A;
    margin-bottom: 10px;
}

.post h2 a {
    color: #3A663A;
    text-decoration: none;
}

.post h2 a:hover {
    color: #2A4A2A;
}

.post-meta {
    color: #666;
    font-size: 14px;
    margin-bottom: 15px;
}

.post-excerpt {
    color: #666;
    line-height: 1.6;
    margin-bottom: 20px;
}

.read-more {
    color: #3A663A;
    text-decoration: none;
    font-weight: 500;
}

.read-more:hover {
    color: #2A4A2A;
}
</style>
