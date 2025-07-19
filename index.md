---
layout: default
title: Главная
---

# Добро пожаловать в osu! Store

Это магазин битмапов, протестированных с портом osu! от nuudles.

Все битмапы доступны для установки через .zip файл, инструкция доступна ниже.

## Доступные битмапы:

{% for post in site.posts reversed %}
- **[{{ post.title }}]({{ post.url | relative_url }})**
{% endfor %}

## Полезные ссылки:
- [**Инструкция по установке битмапов**]({{ '/installation/' | relative_url }})
- [**FAQ**]({{ '/faq/' | relative_url }})
