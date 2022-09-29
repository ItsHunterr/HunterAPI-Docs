---
description: Get a random word
---

# 🔃 Random Word

## Making the request

****[**https://hunterapi.tk/api/random-word**](https://hunterapi.tk/api/random-word)****

{% swagger method="get" path="/random-word" baseUrl="https://hunterapi.tk/api" summary="Get a random word" %}
{% swagger-description %}

{% endswagger-description %}

{% swagger-response status="200: OK" description="" %}
```json
{
  "word": "manuscript",
  "link": "https://en.wikipedia.org/wiki/manuscript"
}
```
{% endswagger-response %}
{% endswagger %}

## Example

```javascript
const fetch = require("node-fetch")
const api_response = await fetch(`https://hunterapi.tk/api/random-word`).then(r => r.json())
```

### Output

```json
{
  "word": "manuscript",
  "link": "https://en.wikipedia.org/wiki/manuscript"
}
```
