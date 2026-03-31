---
metaLinks:
  alternates:
    - >-
      https://app.gitbook.com/s/lFrvHjmleJ8kyUqi4DYv/for-developers/documentation-api-v1/mrp-stats-api-v1
---

# 📊 MRP API Stats V1

<h3 id="api" align="center"><strong>Справка по API</strong></h3>

Команда ER:LC Россия и подпроектов (в т.ч. Moscow RolePlay) **не оказывает поддержку** по написанию кода или интеграции API в сторонние решения.

{% hint style="warning" %}
**POST-эндпоинты имеют другие лимиты запросов. Обязательно читайте и строго соблюдайте все заголовки Rate Limit.**
{% endhint %}

{% openapi-operation spec="en-stats-openapi" path="/moscowroleplay/stats/playercount" method="get" %}
[OpenAPI en-stats-openapi](https://4401d86825a13bf607936cc3a9f3897a.r2.cloudflarestorage.com/gitbook-x-prod-openapi/raw/5c75440b08397a35ea077e4ea64f455a213376433e69f2f05526481367162fd9.yaml?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=dce48141f43c0191a2ad043a6888781c%2F20260331%2Fauto%2Fs3%2Faws4_request&X-Amz-Date=20260331T145710Z&X-Amz-Expires=172800&X-Amz-Signature=212694fd64e8dffee51e2ccebbea624b34dc7670cf4489ef10ff12fa3d1dd362&X-Amz-SignedHeaders=host&x-amz-checksum-mode=ENABLED&x-id=GetObject)
{% endopenapi-operation %}

{% openapi-operation spec="en-stats-openapi" path="/moscowroleplay/stats/{server}/membercount" method="get" %}
[OpenAPI en-stats-openapi](https://4401d86825a13bf607936cc3a9f3897a.r2.cloudflarestorage.com/gitbook-x-prod-openapi/raw/5c75440b08397a35ea077e4ea64f455a213376433e69f2f05526481367162fd9.yaml?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=dce48141f43c0191a2ad043a6888781c%2F20260331%2Fauto%2Fs3%2Faws4_request&X-Amz-Date=20260331T145710Z&X-Amz-Expires=172800&X-Amz-Signature=212694fd64e8dffee51e2ccebbea624b34dc7670cf4489ef10ff12fa3d1dd362&X-Amz-SignedHeaders=host&x-amz-checksum-mode=ENABLED&x-id=GetObject)
{% endopenapi-operation %}

{% openapi-operation spec="en-stats-openapi" path="/moscowroleplay/stats/{server}/allmembercount" method="get" %}
[OpenAPI en-stats-openapi](https://4401d86825a13bf607936cc3a9f3897a.r2.cloudflarestorage.com/gitbook-x-prod-openapi/raw/5c75440b08397a35ea077e4ea64f455a213376433e69f2f05526481367162fd9.yaml?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=dce48141f43c0191a2ad043a6888781c%2F20260331%2Fauto%2Fs3%2Faws4_request&X-Amz-Date=20260331T145710Z&X-Amz-Expires=172800&X-Amz-Signature=212694fd64e8dffee51e2ccebbea624b34dc7670cf4489ef10ff12fa3d1dd362&X-Amz-SignedHeaders=host&x-amz-checksum-mode=ENABLED&x-id=GetObject)
{% endopenapi-operation %}

{% openapi-operation spec="en-stats-openapi" path="/moscowroleplay/stats/{server}/botcount" method="get" %}
[OpenAPI en-stats-openapi](https://4401d86825a13bf607936cc3a9f3897a.r2.cloudflarestorage.com/gitbook-x-prod-openapi/raw/5c75440b08397a35ea077e4ea64f455a213376433e69f2f05526481367162fd9.yaml?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=dce48141f43c0191a2ad043a6888781c%2F20260331%2Fauto%2Fs3%2Faws4_request&X-Amz-Date=20260331T145710Z&X-Amz-Expires=172800&X-Amz-Signature=212694fd64e8dffee51e2ccebbea624b34dc7670cf4489ef10ff12fa3d1dd362&X-Amz-SignedHeaders=host&x-amz-checksum-mode=ENABLED&x-id=GetObject)
{% endopenapi-operation %}

***

<p align="center"><sub>© 2026 ER:LC Россия. Все права защищены.</sub></p>
