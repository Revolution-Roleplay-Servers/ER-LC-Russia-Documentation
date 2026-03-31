---
metaLinks:
  alternates:
    - >-
      https://app.gitbook.com/s/lFrvHjmleJ8kyUqi4DYv/for-developers/documentation-api-v1/mrp-erlc-api-v1
---

# 🚗 MRP ER:LC API V1

<h3 id="api" align="center"><strong>Аутентификация API</strong></h3>

Все запросы к API должны содержать валидный заголовок **Authentication**.

**Не знаете, где взять API ключ?**

Инструкция по получению API-ключа здесь: [.](./ "mention").

<h3 id="api" align="center"><strong>Справка по API</strong></h3>

Команда ER:LC Россия и подпроектов (в т.ч. Moscow RolePlay) **не оказывает поддержку** по написанию кода или интеграции API в сторонние решения.

{% hint style="warning" %}
**POST-эндпоинты имеют другие лимиты запросов. Обязательно читайте и строго соблюдайте все заголовки Rate Limit.**
{% endhint %}

{% openapi-operation spec="erlc-russia-server-api" path="/moscowroleplay/erlc/server/command" method="post" %}
[OpenAPI erlc-russia-server-api](https://4401d86825a13bf607936cc3a9f3897a.r2.cloudflarestorage.com/gitbook-x-prod-openapi/raw/ba18bfd40e17e1ba2846420812f3c8ec4e8bfd74dc312fe1ee7333c186e1adb1.yaml?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=dce48141f43c0191a2ad043a6888781c%2F20260331%2Fauto%2Fs3%2Faws4_request&X-Amz-Date=20260331T142855Z&X-Amz-Expires=172800&X-Amz-Signature=5a4a7c96f85f42e325578cb92a30fb5f6738558311a1791817bc8331f66f2018&X-Amz-SignedHeaders=host&x-amz-checksum-mode=ENABLED&x-id=GetObject)
{% endopenapi-operation %}

{% openapi-operation spec="erlc-russia-server-api" path="/moscowroleplay/erlc/server" method="get" %}
[OpenAPI erlc-russia-server-api](https://4401d86825a13bf607936cc3a9f3897a.r2.cloudflarestorage.com/gitbook-x-prod-openapi/raw/ba18bfd40e17e1ba2846420812f3c8ec4e8bfd74dc312fe1ee7333c186e1adb1.yaml?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=dce48141f43c0191a2ad043a6888781c%2F20260331%2Fauto%2Fs3%2Faws4_request&X-Amz-Date=20260331T142855Z&X-Amz-Expires=172800&X-Amz-Signature=5a4a7c96f85f42e325578cb92a30fb5f6738558311a1791817bc8331f66f2018&X-Amz-SignedHeaders=host&x-amz-checksum-mode=ENABLED&x-id=GetObject)
{% endopenapi-operation %}

{% openapi-operation spec="erlc-russia-server-api" path="/moscowroleplay/erlc/server/players" method="get" %}
[OpenAPI erlc-russia-server-api](https://4401d86825a13bf607936cc3a9f3897a.r2.cloudflarestorage.com/gitbook-x-prod-openapi/raw/ba18bfd40e17e1ba2846420812f3c8ec4e8bfd74dc312fe1ee7333c186e1adb1.yaml?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=dce48141f43c0191a2ad043a6888781c%2F20260331%2Fauto%2Fs3%2Faws4_request&X-Amz-Date=20260331T142855Z&X-Amz-Expires=172800&X-Amz-Signature=5a4a7c96f85f42e325578cb92a30fb5f6738558311a1791817bc8331f66f2018&X-Amz-SignedHeaders=host&x-amz-checksum-mode=ENABLED&x-id=GetObject)
{% endopenapi-operation %}

{% openapi-operation spec="erlc-russia-server-api" path="/moscowroleplay/erlc/server/joinlogs" method="get" %}
[OpenAPI erlc-russia-server-api](https://4401d86825a13bf607936cc3a9f3897a.r2.cloudflarestorage.com/gitbook-x-prod-openapi/raw/ba18bfd40e17e1ba2846420812f3c8ec4e8bfd74dc312fe1ee7333c186e1adb1.yaml?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=dce48141f43c0191a2ad043a6888781c%2F20260331%2Fauto%2Fs3%2Faws4_request&X-Amz-Date=20260331T142855Z&X-Amz-Expires=172800&X-Amz-Signature=5a4a7c96f85f42e325578cb92a30fb5f6738558311a1791817bc8331f66f2018&X-Amz-SignedHeaders=host&x-amz-checksum-mode=ENABLED&x-id=GetObject)
{% endopenapi-operation %}

{% openapi-operation spec="erlc-russia-server-api" path="/moscowroleplay/erlc/server/queue" method="get" %}
[OpenAPI erlc-russia-server-api](https://4401d86825a13bf607936cc3a9f3897a.r2.cloudflarestorage.com/gitbook-x-prod-openapi/raw/ba18bfd40e17e1ba2846420812f3c8ec4e8bfd74dc312fe1ee7333c186e1adb1.yaml?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=dce48141f43c0191a2ad043a6888781c%2F20260331%2Fauto%2Fs3%2Faws4_request&X-Amz-Date=20260331T142855Z&X-Amz-Expires=172800&X-Amz-Signature=5a4a7c96f85f42e325578cb92a30fb5f6738558311a1791817bc8331f66f2018&X-Amz-SignedHeaders=host&x-amz-checksum-mode=ENABLED&x-id=GetObject)
{% endopenapi-operation %}

{% openapi-operation spec="erlc-russia-server-api" path="/moscowroleplay/erlc/server/killlogs" method="get" %}
[OpenAPI erlc-russia-server-api](https://4401d86825a13bf607936cc3a9f3897a.r2.cloudflarestorage.com/gitbook-x-prod-openapi/raw/ba18bfd40e17e1ba2846420812f3c8ec4e8bfd74dc312fe1ee7333c186e1adb1.yaml?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=dce48141f43c0191a2ad043a6888781c%2F20260331%2Fauto%2Fs3%2Faws4_request&X-Amz-Date=20260331T142855Z&X-Amz-Expires=172800&X-Amz-Signature=5a4a7c96f85f42e325578cb92a30fb5f6738558311a1791817bc8331f66f2018&X-Amz-SignedHeaders=host&x-amz-checksum-mode=ENABLED&x-id=GetObject)
{% endopenapi-operation %}

{% openapi-operation spec="erlc-russia-server-api" path="/moscowroleplay/erlc/server/commandlogs" method="get" %}
[OpenAPI erlc-russia-server-api](https://4401d86825a13bf607936cc3a9f3897a.r2.cloudflarestorage.com/gitbook-x-prod-openapi/raw/ba18bfd40e17e1ba2846420812f3c8ec4e8bfd74dc312fe1ee7333c186e1adb1.yaml?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=dce48141f43c0191a2ad043a6888781c%2F20260331%2Fauto%2Fs3%2Faws4_request&X-Amz-Date=20260331T142855Z&X-Amz-Expires=172800&X-Amz-Signature=5a4a7c96f85f42e325578cb92a30fb5f6738558311a1791817bc8331f66f2018&X-Amz-SignedHeaders=host&x-amz-checksum-mode=ENABLED&x-id=GetObject)
{% endopenapi-operation %}

{% openapi-operation spec="erlc-russia-server-api" path="/moscowroleplay/erlc/server/modcalls" method="get" %}
[OpenAPI erlc-russia-server-api](https://4401d86825a13bf607936cc3a9f3897a.r2.cloudflarestorage.com/gitbook-x-prod-openapi/raw/ba18bfd40e17e1ba2846420812f3c8ec4e8bfd74dc312fe1ee7333c186e1adb1.yaml?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=dce48141f43c0191a2ad043a6888781c%2F20260331%2Fauto%2Fs3%2Faws4_request&X-Amz-Date=20260331T142855Z&X-Amz-Expires=172800&X-Amz-Signature=5a4a7c96f85f42e325578cb92a30fb5f6738558311a1791817bc8331f66f2018&X-Amz-SignedHeaders=host&x-amz-checksum-mode=ENABLED&x-id=GetObject)
{% endopenapi-operation %}

{% openapi-operation spec="erlc-russia-server-api" path="/moscowroleplay/erlc/server/bans" method="get" %}
[OpenAPI erlc-russia-server-api](https://4401d86825a13bf607936cc3a9f3897a.r2.cloudflarestorage.com/gitbook-x-prod-openapi/raw/ba18bfd40e17e1ba2846420812f3c8ec4e8bfd74dc312fe1ee7333c186e1adb1.yaml?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=dce48141f43c0191a2ad043a6888781c%2F20260331%2Fauto%2Fs3%2Faws4_request&X-Amz-Date=20260331T142855Z&X-Amz-Expires=172800&X-Amz-Signature=5a4a7c96f85f42e325578cb92a30fb5f6738558311a1791817bc8331f66f2018&X-Amz-SignedHeaders=host&x-amz-checksum-mode=ENABLED&x-id=GetObject)
{% endopenapi-operation %}

{% openapi-operation spec="erlc-russia-server-api" path="/moscowroleplay/erlc/server/vehicles" method="get" %}
[OpenAPI erlc-russia-server-api](https://4401d86825a13bf607936cc3a9f3897a.r2.cloudflarestorage.com/gitbook-x-prod-openapi/raw/ba18bfd40e17e1ba2846420812f3c8ec4e8bfd74dc312fe1ee7333c186e1adb1.yaml?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=dce48141f43c0191a2ad043a6888781c%2F20260331%2Fauto%2Fs3%2Faws4_request&X-Amz-Date=20260331T142855Z&X-Amz-Expires=172800&X-Amz-Signature=5a4a7c96f85f42e325578cb92a30fb5f6738558311a1791817bc8331f66f2018&X-Amz-SignedHeaders=host&x-amz-checksum-mode=ENABLED&x-id=GetObject)
{% endopenapi-operation %}

{% openapi-operation spec="erlc-russia-server-api" path="/moscowroleplay/erlc/server/staff" method="get" %}
[OpenAPI erlc-russia-server-api](https://4401d86825a13bf607936cc3a9f3897a.r2.cloudflarestorage.com/gitbook-x-prod-openapi/raw/ba18bfd40e17e1ba2846420812f3c8ec4e8bfd74dc312fe1ee7333c186e1adb1.yaml?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=dce48141f43c0191a2ad043a6888781c%2F20260331%2Fauto%2Fs3%2Faws4_request&X-Amz-Date=20260331T142855Z&X-Amz-Expires=172800&X-Amz-Signature=5a4a7c96f85f42e325578cb92a30fb5f6738558311a1791817bc8331f66f2018&X-Amz-SignedHeaders=host&x-amz-checksum-mode=ENABLED&x-id=GetObject)
{% endopenapi-operation %}

***

<p align="center"><sub>© 2026 ER:LC Россия. Все права защищены.</sub></p>
