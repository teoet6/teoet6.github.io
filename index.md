---
title: Съдържание
---

На тази страница ще има повече неща, но засега има само

## 🎮 Игри

[Игра с лазери](/laser-game)

## 📝 Статии

{% for post in site.posts %}
### [{{ post.date | date: "%Y-%m-%d" }} | {% include lat2cyr lat=post.title %}]({{ post.url }})

{{ post.excerpt }}

{% endfor %}
