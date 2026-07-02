---
layout: default
title: John Stansbury
---

# John Stansbury

Welcome to my GitHub Pages profile. I build things, break things, fix things, and occasionally make them look good. This site is my hub for projects, experiments, writing, and whatever else I’m tinkering with.

---

## 🧰 Projects & Work
- Web tinkering with Jekyll, Markdown, and static sites  
- Creative world-building (Greenland project)  
- MLB analytics, roster building, and youth movement studies  
- Church governance modernization and digital workflows  
- Mac/iOS tools, utilities, and workspace experiments  

---

## 📬 Connect
You can find me on GitHub or reach out through the usual channels.

---

## 📝 Latest Posts
{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%B %d, %Y" }}
{% endfor %}
