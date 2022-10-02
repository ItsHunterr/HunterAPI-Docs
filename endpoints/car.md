---
description: Get a random car
---

# 🏎 Car

## Making the request

****[**https://hunterapi.tk/api/random-car**](https://hunterapi.tk/api/random-car)****

{% swagger method="get" path="/random-car" baseUrl="https://hunterapi.tk/api" summary="Get a random car" %}
{% swagger-description %}

{% endswagger-description %}


{% swagger-response status="200: OK" description="" %}
```json
{
  "success": true,
  "image_link": "https://i.redd.it/6ibcvuofg5h91.jpg",
  "image_title": "Arash Imperium"
}
```
{% endswagger-response %}
{% endswagger %}

## Example

```javascript
const fetch = require("node-fetch")
const api_response = await fetch(`https://hunterapi.tk/api/random-car`).then(r => r.json())
```

### Output

```json
{
  "success": true,
  "image_link": "https://i.redd.it/6ibcvuofg5h91.jpg",
  "image_title": "Arash Imperium"
}
```

