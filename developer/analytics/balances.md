# Balances

{% swagger method="get" path="" baseUrl="https://api.wallety.org/balances" summary="" %}
{% swagger-description %}

{% endswagger-description %}

{% swagger-parameter in="path" name="api_key=" type="String" required="true" %}
YOUR_API_KEY
{% endswagger-parameter %}

{% swagger-parameter in="path" name="network=" type="String" required="true" %}
Network (e.g "polkadot")
{% endswagger-parameter %}

{% swagger-parameter in="path" name="wallet_address=" type="String" required="true" %}
WALLET_ADDRESS
{% endswagger-parameter %}

{% swagger-parameter in="path" name="currency=" type="String" %}
dollar/euro/pound (defaults to dollar)
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="Example response >" %}
```javascript
{
'total_balance': {'coin_amount': '', 'coin_amount_dollar': ''},
'transferable_balance': {'coin_amount': '', 'coin_amount_dollar': ''},
'locked_balance': {'coin_amount': '', 'coin_amount_dollar': ''},
'reserved_balance': {'coin_amount': '', 'coin_amount_dollar': ''}
}
```
{% endswagger-response %}
{% endswagger %}
