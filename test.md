---
title: 测试
---

---
title: 归档
layout: default
---

{% include header.html %}

<div class="g-banner tags-banner {{ site.postPatterns | prepend: 'post-pattern-' }} {{ site.theme-color | prepend: 'bgcolor-' }}"
     data-theme="{{ site.theme-color }}">
    <h2>归档</h2>
</div>

<main class="tags-content">
    <ul class="tags-list">
        <li style="text-align: center;">共 {{ site.posts.size }} 篇文章</li>
        <li>
        {% for post in site.posts %}
        {% capture this_year %}{{ post.date | date: "%Y" }}{% endcapture %}
        {% capture this_month %}{{ post.date | date: "%B" }}{% endcapture %}
        {% capture next_year %}{{ post.previous.date | date: "%Y" }}{% endcapture %}
        {% capture next_month %}{{ post.previous.date | date: "%B" }}{% endcapture %}
        {% if forloop.first %}
        <span class="archive-name" id="{{ post.date | date: "%Y-%m" }}">「{{ post.date | date: "%Y年%m月" }}」</span>
        {% endif %}
        <a class="archive-post" href="{{ post.url }}">{{ post.date | date: "%m-%d" }} » {{ post.title }}</a>
        {% if forloop.last %}
        </li>
        {% else %}
        {% if this_year != next_year %}
        </li>
        <li>
        <span class="archive-name" id="{{post.previous.date | date: "%Y-%m" }}">「{{ post.previous.date | date: "%Y年%m月" }}」</span>
        {% else %}
        {% if this_month != next_month %}
        </li>
        <li>
        <span class="archive-name" id="{{ post.previous.date | date: "%Y-%m" }}">「{{ post.previous.date | date: "%Y年%m月" }}」</span>
        {% endif %}
        {% endif %}
        {% endif %}
        {% endfor %}
        </li>
    </li>
    </ul>
</main>

{% include footer.html %}