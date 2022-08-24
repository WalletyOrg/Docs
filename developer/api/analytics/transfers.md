# Transfers

{% swagger method="get" path="" baseUrl="https://api.wallety.org/transfers" summary="" %}
{% swagger-description %}

{% endswagger-description %}

{% swagger-parameter in="path" name="api_key=" type="String" required="true" %}
YOUR_API_KEY{ 
{% endswagger-parameter %}

{% swagger-parameter in="path" name="network=" type="String" required="true" %}
Network (e.g "polkadot")
{% endswagger-parameter %}

{% swagger-parameter in="path" name="wallet_address=" required="true" type="String" %}
WALLET_ADDRESS
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="Example response >" %}
<pre class="language-javascript"><code class="lang-javascript">{

'withdraw_transfers': [{'coin_amount': '', 'coin_worth_dollar': '', 
'display_name': '', 'wallet_address': '', 'txn_time': '', 'days_since': '',
'gas_fee': '', 'gas_fee_fiat': ''}], 

<strong>'deposit_transfers': [{'display_name': '', 'wallet_address': '', 
</strong><strong>'deposited': '', 'deposited_fiat_worth': '', 'txn_time': '',
</strong>'days_since': '', 'gas_fee': '', 'gas_dollar_worth': ''}],
 
}</code></pre>
{% endswagger-response %}
{% endswagger %}
