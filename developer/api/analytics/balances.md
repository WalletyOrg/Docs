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
'total_balance': {'coin': '', 'fiat_worth': ''},
'transferable_balance': {'coin': '', 'fiat_worth': ''},
'locked_balance': {'coin': '', 'fiat_worth': ''},
'reserved_balance': {'coin': '', 'fiat_worth': ''}
}
```
{% endswagger-response %}
{% endswagger %}
