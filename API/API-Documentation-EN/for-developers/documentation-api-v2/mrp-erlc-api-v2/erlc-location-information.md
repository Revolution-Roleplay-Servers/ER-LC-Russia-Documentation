---
description: В API V2 добавляется информация локации игрока!
metaLinks:
  alternates:
    - >-
      https://app.gitbook.com/s/lFrvHjmleJ8kyUqi4DYv/for-developers/documentation-api-v2/mrp-erlc-api-v2/erlc-location-information
---

# 🗺️ Информация о Локации ER:LC

**Локация каждого игрока будет выглядеть примерно так:**

```json
{
  "LocationX": 1084.965,
  "LocationZ": 2302.28,
  "PostalCode": "218",
  "StreetName": "Park Street",
  "BuildingNumber": "2083"
}
```

Поля **LocationX** и **LocationZ** соответствуют координатам **X** и **Z** на одном из официальных изображений карты.

{% tabs %}
{% tab title="Осень" %}
Пример Карты: [https://maps.erlcrussia.xyz/fall\_blank](https://maps.erlcrussia.xyz/fall_blank)

Почтовые Индексы (Postals) + Улицы (Streets): [https://maps.erlcrussia.xyz/fall\_postals](https://maps.erlcrussia.xyz/fall_postals)
{% endtab %}

{% tab title="Зима" %}
Пример Карты: [https://maps.erlcrussia.xyz/snow\_blank](https://maps.erlcrussia.xyz/snow_blank)

Почтовые Индексы (Postals) + Улицы (Streets): [https://maps.erlcrussia.xyz/snow\_postals](https://maps.erlcrussia.xyz/snow_postals)
{% endtab %}
{% endtabs %}

***

<p align="center"><sub>© 2026 ER:LC Россия. Все права защищены.</sub></p>
