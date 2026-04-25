---
layout: home
title: Home
---

# 🚀 Welcome to KORENET

![Banner](https://raw.githubusercontent.com/CaveBearGaming/cavebeargaming.github.io/refs/heads/main/dark-blue-technology-high-tech-abstract-banner-background_28629-1326.avif)

Tech blogs, experiments, and projects.

---

## 📰 Latest posts

{% for post in site.posts limit:5 %}
### [{{ post.title }}]({{ post.url | relative_url }})
{{ post.date | date: "%Y-%m-%d" }}

---
{% endfor %}
