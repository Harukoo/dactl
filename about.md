---
layout: page
title: About
permalink: /about/
published: true
---

<div class="page" markdown="1">

{% capture page_subtitle %}
<img
    class="me"
    alt="{{ author.name }}"
    src="{{ site.author.photo | relative_url }}"
    srcset="{{ site.author.photo2x | relative_url }} 2x"
/>
{% endcapture %}

{% include page/title.html title=page.title subtitle=page_subtitle %}

## 关于我

我是东北师范大学的大学僧，欢迎来到我的博客，在这里你可以看到我的作品，以及我的生活日常<br>

# 关于博客技术支持 请找我哥 
他的博客 https://lfjd05.github.io/Lui-Yi-Pages/home/ <br>
他的知乎 现场可编程逻辑
</div>
