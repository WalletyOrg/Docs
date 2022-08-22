# Paper/diamond handed

{% swagger method="get" path="" baseUrl="/diamond-handed" summary="" %}
{% swagger-description %}

{% endswagger-description %}

{% swagger-parameter in="path" name="api_key=" required="true" type="String" %}

{% endswagger-parameter %}

{% swagger-parameter in="path" name="wallet_address=" required="true" type="String" %}

{% endswagger-parameter %}

{% swagger-response status="200: OK" description="" %}
```javascript
{
"diamond_handed: ""
}
```
{% endswagger-response %}
{% endswagger %}

{% swagger method="get" path="" baseUrl="/paper-handed" summary="" %}
{% swagger-description %}

{% endswagger-description %}

{% swagger-parameter in="path" name="api_key=" type="String" required="true" %}

{% endswagger-parameter %}

{% swagger-parameter in="path" name="wallet_address=" required="true" type="String" %}

{% endswagger-parameter %}

{% swagger-response status="200: OK" description="" %}
```javascript
{
"paper_handed": ""
}
```
{% endswagger-response %}
{% endswagger %}
