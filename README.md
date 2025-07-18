---
layout: default
title: Список Битмапов
---

# Добро пожаловать в osu! Legacy Store!

Это неофициальный архив битмапов, адаптированных для старых версий osu! на Legacy iOS устройствах (iPhone/iPad).

Все битмапы доступны для ручной установки через .zip файл, а также для автоматической установки на джейлбрейкнутые устройства с OpenSSH.

## Доступные битмапы:

{% for post in site.posts reversed %}
- **[{{ post.title }}]({{ post.url | relative_url }})**
{% endfor %}

---

*P.S. Этот сайт создан для фанатов Legacy iOS и osu!*
