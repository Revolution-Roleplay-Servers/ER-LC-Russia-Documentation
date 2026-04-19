# 🏎️ MRP ER:LC API V2

<h3 id="api" align="center"><strong>Аутентификация API</strong></h3>

Все запросы к API должны содержать валидный заголовок **Authentication c MRPAPIKey**.

{% hint style="info" %}
**Не знаете, где взять API ключ?**\
Инструкция по получению API-ключа lдоступна здесь: [..](../ "mention").
{% endhint %}

<h3 align="center"><strong>Что нового в API v2?</strong></h3>

В новой версии API теперь доступны часто запрашиваемые данные, включая **местоположение игроков** и **цвета транспортных средств**!

API V1 продолжит работу **без существенных изменений** до дальнейших объявлений со стороны PRC или нашей команды.

<h3 align="center">Информация Об Эндпоинтах</h3>

Также смотрите: [erlc-location-information.md](erlc-location-information.md "mention")

{% openapi-operation spec="erlc-russia-v2-server-api" path="/moscowroleplay/erlc/server" method="get" %}
[OpenAPI erlc-russia-v2-server-api](https://4401d86825a13bf607936cc3a9f3897a.r2.cloudflarestorage.com/gitbook-x-prod-openapi/raw/556e7f0461934e1e525fa9dbc560f5c3a1dda944e571805bb304adf780fc6704.yaml?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=dce48141f43c0191a2ad043a6888781c%2F20260419%2Fauto%2Fs3%2Faws4_request&X-Amz-Date=20260419T155356Z&X-Amz-Expires=172800&X-Amz-Signature=db4ee6a841fe1115ec9e1e44ce61e9a26fa4cd4a289221db754c700b0f48777a&X-Amz-SignedHeaders=host&x-amz-checksum-mode=ENABLED&x-id=GetObject)
{% endopenapi-operation %}

{% openapi-operation spec="erlc-russia-v2-server-api" path="/moscowroleplay/erlc/server/command" method="post" %}
[OpenAPI erlc-russia-v2-server-api](https://4401d86825a13bf607936cc3a9f3897a.r2.cloudflarestorage.com/gitbook-x-prod-openapi/raw/556e7f0461934e1e525fa9dbc560f5c3a1dda944e571805bb304adf780fc6704.yaml?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=dce48141f43c0191a2ad043a6888781c%2F20260419%2Fauto%2Fs3%2Faws4_request&X-Amz-Date=20260419T155356Z&X-Amz-Expires=172800&X-Amz-Signature=db4ee6a841fe1115ec9e1e44ce61e9a26fa4cd4a289221db754c700b0f48777a&X-Amz-SignedHeaders=host&x-amz-checksum-mode=ENABLED&x-id=GetObject)
{% endopenapi-operation %}

***

<p align="center"><sub>© 2026 ER:LC Россия. Все права защищены.</sub></p>
