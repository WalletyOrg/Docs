# Monthly transfer data

{% swagger method="get" path="" baseUrl="/monthly-transfers" summary="" %}
{% swagger-description %}

{% endswagger-description %}

{% swagger-parameter in="path" name="api_key=" type="String" required="true" %}

{% endswagger-parameter %}

{% swagger-parameter in="path" name="wallet_address=" type="String" required="true" %}

{% endswagger-parameter %}

{% swagger-response status="200: OK" description="" %}
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
