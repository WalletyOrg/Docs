# Custom unique wallets

{% swagger method="get" path="" baseUrl="https://api.wallety.org/custom-unique-wallets" summary="" %}
{% swagger-description %}

{% endswagger-description %}

{% swagger-parameter in="path" required="true" name="api_key=" type="String" %}
YOUR_API_KEY
{% endswagger-parameter %}

{% swagger-parameter in="path" name="wallet_address=" type="String" required="true" %}
WALLET_ADDRESS
{% endswagger-parameter %}

{% swagger-parameter in="path" type="String" name="network=" required="true" %}
Network (e.g "polkadot")
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="Example response >" %}
```javascript
{
"total": {"display_name": "", "wallet_address": "", "volume": "", "volume_fiat_value": "", "percentage_weight": "fee", "fee_fiat_value": "", interaction_amount": "", "failure_amount" : "", "first_transaction": ["date": "", "time": "", "days_since": ""], "last_transaction": ["date": "", "time": "", "days_since": ""]}, 
"deposits": {"display_name": "", "wallet_address": "", "volume": "", "volume_fiat_value": "", "percentage_weight": "fee", "fee_fiat_value": "", interaction_amount": "", "failure_amount" : "", "first_transaction": ["date": "", "time": "", "days_since": ""], "last_transaction": ["date": "", "time": "", "days_since": ""]}, 
"withdrawals": {"display_name": "", "wallet_address": "", "volume": "", "volume_fiat_value": "", "percentage_weight": "fee", "fee_fiat_value": "", interaction_amount": "", "failure_amount" : "", "first_transaction": ["date": "", "time": "", "days_since": ""], "last_transaction": ["date": "", "time": "", "days_since": ""]}, 
}
```
{% endswagger-response %}
{% endswagger %}
