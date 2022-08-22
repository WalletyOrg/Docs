# Total unique wallets

{% swagger method="get" path="" baseUrl="/total-unique-wallets" summary="" %}
{% swagger-description %}

{% endswagger-description %}

{% swagger-parameter in="path" name="api_key=" required="true" type="String" %}

{% endswagger-parameter %}

{% swagger-parameter in="path" name="wallet_address=" type="String" required="true" %}

{% endswagger-parameter %}

{% swagger-response status="200: OK" description="" %}
```javascript
{
"total": {"display_name": "", "wallet_address": "", "volume": "", "volume_fiat_value": "", "percentage_weight": "fee", "fee_fiat_value": "", interaction_amount": "", "failure_amount" : "", "first_transaction": ["date": "", "time": "", "days_since": ""], "last_transaction": ["date": "", "time": "", "days_since": ""]}, 
"deposits": {"display_name": "", "wallet_address": "", "volume": "", "volume_fiat_value": "", "percentage_weight": "fee", "fee_fiat_value": "", interaction_amount": "", "failure_amount" : "", "first_transaction": ["date": "", "time": "", "days_since": ""], "last_transaction": ["date": "", "time": "", "days_since": ""]}, 
"withdrawals": {"display_name": "", "wallet_address": "", "volume": "", "volume_fiat_value": "", "percentage_weight": "fee", "fee_fiat_value": "", interaction_amount": "", "failure_amount" : "", "first_transaction": ["date": "", "time": "", "days_since": ""], "last_transaction": ["date": "", "time": "", "days_since": ""]}, 
}
```
{% endswagger-response %}
{% endswagger %}
