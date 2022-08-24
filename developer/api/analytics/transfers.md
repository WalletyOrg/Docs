# Transfers

{% swagger method="get" path="" baseUrl="https://api.wallety.org/transfers" summary="" %}
{% swagger-description %}

{% endswagger-description %}

{% swagger-parameter in="path" name="api_key=" type="String" required="true" %}
YOUR_API_KEY
{% endswagger-parameter %}

{% swagger-parameter in="path" name="network=" type="String" required="true" %}
Network (e.g "polkadot")
{% endswagger-parameter %}

{% swagger-parameter in="path" name="wallet_address=" required="true" type="String" %}
WALLET_ADDRESS
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="Example response >" %}
```javascript
{
"deposits": {"display_name": "", "wallet_address": "", "amount": "", "amount_fiat_worth": "", "date": "", "time": "", "days_since": "", "fee": "", "fee_fiat_worth"}, 
"withdrawals": {"display_name": "", "wallet_address": "", "amount": "", "amount_fiat_worth": "", "date": "", "time": "", "days_since": "", "fee": "", "fee_fiat_worth"}
}
```
{% endswagger-response %}
{% endswagger %}
