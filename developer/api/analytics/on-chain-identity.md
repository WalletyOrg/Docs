# On chain identity

Specified wallet addresses on chain display name, legal name, index, users role, and social media profiles

{% swagger method="get" path="" baseUrl="/on-chain-identity" summary="" %}
{% swagger-description %}

{% endswagger-description %}

{% swagger-parameter in="path" name="api_key=" type="String" required="true" %}
YOUR_API_KEY
{% endswagger-parameter %}

{% swagger-parameter in="path" name="wallet_address=" type="String" required="true" %}
WALLET_ADDRESS
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="Example response >" %}
```javascript
{
"display_name": "",
"legal_name": "",
"index": ""
"role": ""
"socials": {"twitter": "", "website": "", "email": "", "element": ""}
}
```
{% endswagger-response %}
{% endswagger %}
