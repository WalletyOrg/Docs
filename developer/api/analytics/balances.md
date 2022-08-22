# Balances

{% swagger method="get" path="" baseUrl="/balances" summary="" %}
{% swagger-description %}

{% endswagger-description %}

{% swagger-parameter in="path" name="api_key=" type="String" required="true" %}

{% endswagger-parameter %}

{% swagger-parameter in="path" name="wallet_address=" type="String" required="true" %}

{% endswagger-parameter %}

{% swagger-response status="200: OK" description="" %}
```javascript
{
"total_balance": {"coin": "", "fiat_worth": ""},
"transferable_balance": {"coin": "", "fiat_worth": ""},
"locked_balance": {"coin": "", "fiat_worth": ""},
"reserved_balance": {"coin": "", "fiat_worth": ""}
}
```
{% endswagger-response %}
{% endswagger %}
