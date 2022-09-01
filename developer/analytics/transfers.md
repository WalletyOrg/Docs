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

{% swagger-parameter in="path" name="currency=" type="String" %}
dollar/euro/pound (defaults to dollar)
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="Example response >" %}
```javascript
{
'deposited_transfers': [{'display_name': '', 'wallet_address': '', 
                       'deposited_coin': '', 'deposited_coin_dollar': '', 
                       'txn_time': '', 'days_since': '', 'gas_fee': '', 
                       'gas_fee_dollar': ''}
                       ], 

'withdraw_transfers': [{'withdrawn_coin': '', 'withdrawn_coin_dollar': '', 
                        'display_name': '', 'wallet_address': '', 
                        'txn_time': '', 'days_since': '', 'gas_fee': '', 
                        'gas_fee_dollar': ''}
                        ]
}
```
{% endswagger-response %}
{% endswagger %}
