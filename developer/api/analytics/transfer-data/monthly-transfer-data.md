# Monthly transfer data

{% swagger method="get" path="" baseUrl="https://api.wallety.org/monthly-transfers" summary="" %}
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
