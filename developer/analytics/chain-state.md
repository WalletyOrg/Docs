# Chain state

The specified chains token price, percentage change (24hr), market cap, current block number and last gas paid by a user on chain in token/fiat

{% swagger method="get" path="" baseUrl="https://api.wallety.org/chain-state" summary="" %}
{% swagger-description %}
Chain state
{% endswagger-description %}

{% swagger-parameter in="path" name="api_key=" required="true" type="String" %}
YOUR_API_KEY
{% endswagger-parameter %}

{% swagger-parameter in="path" name="network=" type="String" required="true" %}
Network (e.g "polkadot")
{% endswagger-parameter %}

{% swagger-parameter in="path" name="currency=" type="String" %}
dollar/euro/pound (defaults to dollar)
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="Example response >" %}
```javascript
{
'coin_price_dollar': '',
'percentage_change_24hr': '',
'market_cap_dollar': '',
'transfer_count': '',
'last_gas': {'coin_amount': '', 'coin_amount_dollar': ''}
}
```
{% endswagger-response %}
{% endswagger %}
