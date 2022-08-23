# Custom transfer data

{% swagger method="get" path="" baseUrl="https://api.wallety.org/custom-transfers" summary="" %}
{% swagger-description %}

{% endswagger-description %}

{% swagger-parameter in="path" name="api_key=" required="true" type="String" %}
YOUR_API_KEY
{% endswagger-parameter %}

{% swagger-parameter in="path" name="wallet_address=" required="true" type="String" %}
WALLET_ADDRESS
{% endswagger-parameter %}

{% swagger-parameter in="path" name="network=" required="true" type="String" %}
Network (e.g "polkadot")
{% endswagger-parameter %}

{% swagger-parameter in="path" name="from=" type="String" required="true" %}
YYYY-MM-DD (e.g 2021-07-30)
{% endswagger-parameter %}

{% swagger-parameter in="path" name="to=" required="true" type="String" %}
YYYY-MM-DD (e.g 2022-07-30)
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="Example response >" %}
```javascript
{
"time_period": "",
"total": {"volume": {}, "gas": {}, "failed_gas": {}, "transfers": "", "successful_transfers": "", "failed_transfers": "", "first_transaction": {}, "last_transaction": {}}
"deposit": {"volume": {}, "successful_transfers": "", "first_transaction": {}, "last_transaction": {}}
"withdrawal": {"volume": {}, "gas": {}, "failed_gas": {}, "transfers": "", "successful_transfers": "", "failed_transfers": "", "first_transaction": {}, "last_transaction": {}}
}
```
{% endswagger-response %}
{% endswagger %}
