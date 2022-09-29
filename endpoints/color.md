---
description: Get information from a color
---

# 🎨 Color

## Making the request

****[**https://hunterapi.tk/api/fact**](https://hunterapi.tk/api/fact)****

{% swagger method="get" path="/fact" baseUrl="https://hunterapi.tk/api" summary="Get a random fact" %}
{% swagger-description %}

{% endswagger-description %}

{% swagger-response status="200: OK" description="" %}
```json
{
  "success": true,
  "fact": "The average human has about 20 square feet of skin weighing about 6 pounds."
}
```
{% endswagger-response %}
{% endswagger %}

## Example

```javascript
const fetch = require("node-fetch")
const api_response = await fetch(`https://hunterapi.tk/api/fact`).then(r => r.json())
```

### Output

```json
{
  "success": true,
  "fact": "The average human has about 20 square feet of skin weighing about 6 pounds."
}
```
