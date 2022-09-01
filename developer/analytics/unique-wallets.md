---
description: Unique wallets
---

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
<pre class="language-javascript"><code class="lang-javascript">{
'unique_deposits': [{'display_name': '', 'wallet_address': '', 
                     'total_coin_volume': '', 'total_coin_volume_dollars': '', 
                     'total_percentage_of_deposits': '', 'total_gas_fee': '', 
                     'total_gas_fee_dollar': '', 'total_interaction_times': '', 
                     'total_failed_interaction_times' : '', 
                     'first_txn': {'date': '', 'days_since': ''}, 
                     'last_txn': {'date': '', 'days_since': ''}
                     }], 

'unique_withdrawals': [{'display_name': '', 'wallet_address': '', 
                        'total_coin_volume': '', 'total_coin_volume_dollars': '', 
<strong>                        'total_percentage_of_withdrawals': '', 'total_gas_fee': '', 
</strong>                        'total_gas_fee_dollar': '', 'total_interaction_times': '', 
                        'total_failed_interaction_times' : '', 
                        'first_txn': {'date': '', 'days_since': ''}, 
                        'last_txn': {'date': '', 'days_since': ''}
                        }], 
}</code></pre>
{% endswagger-response %}
{% endswagger %}
