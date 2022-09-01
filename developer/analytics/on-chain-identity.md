---
description: On chain identity
---

# On chain identity

Specified wallet addresses on chain display name, legal name, index, users role, and social media profiles.

{% swagger method="get" path="" baseUrl="https://api.wallety.org/on-chain-identity" summary="" %}
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
<pre class="language-javascript"><code class="lang-javascript"><strong>{
</strong>'display_name': '',
'legal_name': '',
'index': '', 
'role': '', 
'socials': {'twitter': '', 'website': '', 'email': '', 'element': ''}
}</code></pre>
{% endswagger-response %}
{% endswagger %}
