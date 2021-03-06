---
layout: article
titles:
  en:
key: about
---

UX-архитектор офисного пакета МойОфис. Курирует направление исследований, проводит качественные и количественные исследования пользователей, статистически анализирует события и документы, проектирует интерфейсы.

Ранее 5 лет в компании Biarum был главным по дизайну. Участвовал в проектах для медицины: радиология, генетика, системы управления знаниями и лабораториями. Организовывал и наставлял [отдел дизайна](https://www.behance.net/biarum/members) из 2х дизайнеров. Был дизайнером продукта [Powerlineage](https://www.facebook.com/pwrlng/) - автоматизации сбора семейных диаграмм для генетиков-консультантов его [white-label](https://www.invitae.com/en/familyhistory/) версии для генетической лаборатории Invitae, которая в итоге поглотила Powerlineage.

## Интересуется

Работой с большими данными и журналистикой данных, опубликовал статью-исследование.
Эксперементирует с BCI, в контексте применения ЭЭГ в юзабилити исследованиях.
Входит в программный комитет ProfsoUX, курирует сообщество UXSPb.

## Выступает
  <ul>
{% for post in site.posts %}

  {% if post.type == 'talk' or post.type == 'workshop' %}
  <li><a href="{{ post.url }}">{{ post.title }}</a></li>

  {% endif %}
{% endfor %}
