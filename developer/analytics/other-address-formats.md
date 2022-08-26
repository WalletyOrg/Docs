# Other address formats

{% swagger method="get" path="" baseUrl="https://api.wallety.org/other-address-formats" summary="" %}
{% swagger-description %}

{% endswagger-description %}

{% swagger-parameter in="path" name="api_key=" type="String" required="true" %}
YOUR_

_API__

KEY
{% endswagger-parameter %}

{% swagger-parameter in="path" name="wallet_address=" required="true" %}
WALLET_ADDRESS
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="" %}
```javascript
{
    'polkadot_address': '', 
    'kusama_address': ''
}
```
{% endswagger-response %}
{% endswagger %}
