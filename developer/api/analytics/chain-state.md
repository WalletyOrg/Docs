# Chain state

{% swagger method="get" path="" baseUrl="/chain-state" summary="" %}
{% swagger-description %}

{% endswagger-description %}

{% swagger-parameter in="path" name="api_key=" required="true" type="String" %}

{% endswagger-parameter %}

{% swagger-parameter in="path" name="currency=" type="String" %}
dollar/euro/pound
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="" %}
```javascript
{
"coin_price": "",
"percentage_change_24hr": "",
"market_cap": "",
"block_number": "",
"last_gas": {"coin_amount": "", "fiat_worth": ""}
}
```
{% endswagger-response %}
{% endswagger %}
