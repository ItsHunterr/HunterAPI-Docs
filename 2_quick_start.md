# Quick Start
## Make your first request
To make your first request, send an authenticated request to the designated endpoint.
Take a look at how you might call an endpoint using the api with different programming languages.

{% tabs %} 
{% tab title="Javascript (NodeJS)" %}
```javascript
const fetch = require("node-fetch")
const api_response = await fetch(`https://hunterapi.sytes.net/fact`).then(r => r.json())

api_response.fact // Output: On Jupiter and Saturn it rains diamonds.
```
{% endtab %}

{% tab title="Python" %} 
{% endtab %} 
{% tab title="Curl" %} 
{% endtab %} 
{% endtabs %}
