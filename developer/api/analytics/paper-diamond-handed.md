# Paper & diamond handed

{% swagger method="get" path="" baseUrl="https://api.wallety.org/paper-diamond-handed" summary="" %}
{% swagger-description %}

{% endswagger-description %}

{% swagger-parameter in="path" name="api_key=" required="true" type="String" %}
YOUR_API_KEY
{% endswagger-parameter %}

{% swagger-parameter in="path" name="network=" type="String" required="true" %}
Network (e.g "polkadot")
{% endswagger-parameter %}

{% swagger-parameter in="path" name="wallet_address=" required="true" type="String" %}
WALLET_ADDRESS
{% endswagger-parameter %}

{% swagger-parameter in="path" type="String" name="currency=" %}
dollar/euro/pound (defaults to dollar)
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="Example response >" %}
```javascript
{
'paper_handed': {'paper_handed_coins': '',
                 'paper_handed_coins_fiat_worth': ''}, 

'diamond_handed': {'diamond_handed_coins': '',
                   'diamond_handed_coins_fiat_worth': ''}
}
```
{% endswagger-response %}
{% endswagger %}
