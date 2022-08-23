# Server test

Test our server response

{% swagger method="get" path="" baseUrl="https://api.wallety.org" summary="" %}
{% swagger-description %}
Server test
{% endswagger-description %}

{% swagger-parameter in="path" name="api_key=" type="String" required="true" %}
YOUR_

_API_

\_KEY
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="Example response >" %}
<pre class="language-javascript"><code class="lang-javascript">{
<strong>"wallety.org_server_status": 200
</strong>}</code></pre>
{% endswagger-response %}
{% endswagger %}
