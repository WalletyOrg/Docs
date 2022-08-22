# Custom transfer data

{% swagger method="get" path="" baseUrl="/custom-transfers" summary="" %}
{% swagger-description %}

{% endswagger-description %}

{% swagger-parameter in="path" name="api_key=" required="true" type="String" %}

{% endswagger-parameter %}

{% swagger-parameter in="path" name="wallet_address=" required="true" type="String" %}

{% endswagger-parameter %}

{% swagger-parameter in="path" name="from=" type="String" required="true" %}

{% endswagger-parameter %}

{% swagger-parameter in="path" name="to=" required="true" %}

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
