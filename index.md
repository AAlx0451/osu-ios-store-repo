---
layout: default
title: Список Битмапов
---

# Добро пожаловать в osu! iPhone Repo

Это неофициальный архив битмапов, работающих с твиком osu! iPhone.

Все битмапы доступны для ручной установки через .zip файл, инструкция доступна ниже.

## Доступные битмапы:

{% for post in site.posts reversed %}
- **[{{ post.title }}]({{ post.url | relative_url }})**
{% endfor %}

## Полезные ссылки:
- [**Инструкция по установке битмапов**]({{ '/installation/' | relative_url }})
