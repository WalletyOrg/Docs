# On chain identity

{% swagger method="get" path="" baseUrl="/on-chain-identity" summary="" %}
{% swagger-description %}

{% endswagger-description %}

{% swagger-parameter in="path" name="api_key=" type="String" required="true" %}

{% endswagger-parameter %}

{% swagger-parameter in="path" name="wallet_address=" type="String" required="true" %}

{% endswagger-parameter %}

{% swagger-response status="200: OK" description="" %}
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
