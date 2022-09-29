---
description: Get information from a color
---

# 🎨 Color

## Making the request

****[**https://hunterapi.tk/api/color**](https://hunterapi.tk/api/color)****

{% swagger method="get" path="/color" baseUrl="https://hunterapi.tk/api" summary="Get information from a color" %}
{% swagger-description %}

{% endswagger-description %}

{% swagger-parameter in="query" name="hex" type="String" required="true" %}
The hex color code
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="" %}
```json
{
  "success": true,
  "hex": "#FF00FF",
  "rgb": "rgb(255,0,255)",
  "rgba": "rgba(255,0,255,1)",
  "hsl": "hsl(300,100%,50%)",
  "name": "Magenta / Fuchsia",
  "most_similar_color": "#FF00FF",
  "link": "https://hunterapi.tk/api/image/color?hex=FF00FF",
  "disclaimer": "The name provided is not 100% the color entered."
}
```
{% endswagger-response %}
{% endswagger %}

## Example

```javascript
const fetch = require("node-fetch")
const api_response = await fetch(`https://hunterapi.tk/api/color?hex=#FF00FF`).then(r => r.json())
```

### Output

```json
{
  "success": true,
  "hex": "#FF00FF",
  "rgb": "rgb(255,0,255)",
  "rgba": "rgba(255,0,255,1)",
  "hsl": "hsl(300,100%,50%)",
  "name": "Magenta / Fuchsia",
  "most_similar_color": "#FF00FF",
  "link": "https://hunterapi.tk/api/image/color?hex=FF00FF",
  "disclaimer": "The name provided is not 100% the color entered."
}
```
