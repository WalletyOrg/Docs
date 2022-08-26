# Unique wallets

{% swagger method="get" path="" baseUrl="https://api.wallety.org/unique-wallets" summary="" %}
{% swagger-description %}

{% endswagger-description %}

{% swagger-parameter in="path" name="api_key=" required="true" type="String" %}
YOUR_API_KEY
{% endswagger-parameter %}

{% swagger-parameter in="path" name="network=" type="String" required="true" %}
Network (e.g "polkadot")
{% endswagger-parameter %}

{% swagger-parameter in="path" name="wallet_address=" type="String" required="true" %}
WALLET_ADDRESS
{% endswagger-parameter %}

{% swagger-parameter in="path" name="currency=" type="String" %}
dollar/euro/pound (defaults to dollar)
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="Example response >" %}
```javascript
{
'unique_deposits': [{'display_name': '', 'wallet_address': '', 'coin_volume': '', 
                    'coin_volume_dollars': '', 'percentage_of_deposits': '', 
                    'gas_fee': '', 'gas_fee_dollar': '', 'interaction_times': '', 
                    'failed_interaction_times' : '', 
                    'first_txn': {'date': '', 'days_since': ''}, 
                    'last_txn': {'date': '', 'days_since': ''}
                    }], 

'unique_withdrawals': [{'display_name': '', 'wallet_address': '', 'coin_volume': '', 
                    'coin_volume_dollars': '', 'percentage_of_withdrawals': '', 
                    'gas_fee': '', 'gas_fee_dollar': '', 'interaction_times': '', 
                    'failed_interaction_times' : '', 
                    'first_txn': {'date': '', 'days_since': ''}, 
                    'last_txn': {'date': '', 'days_since': ''}
                    }], 
}
```
{% endswagger-response %}
{% endswagger %}
