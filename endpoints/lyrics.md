---
description: Get the lyrics of a song.
---

# 🎶 Lyrics

## Making the request

****[**https://hunterapi.tk/api/lyrics**](https://hunterapi.tk/api/lyrics)****

{% swagger method="get" path="/lyrics" baseUrl="https://hunterapi.tk/api" summary="Get a lyrics" %}
{% swagger-description %}

{% endswagger-description %}

{% swagger-response status="200: OK" description="" %}
```json
{
  "success": true,
  "name": "Hello",
  "author": "Adele",
  "explicit": false,
  "release_date": "2015-10-23T07:00:00Z",
  "genre": "Pop",
  "length": "4:56",
  "thumbnail": "https://is5-ssl.mzstatic.com/image/thumb/Music116/v4/5a/47/6d/5a476ddd-4690-1297-1896-6a286a497a21/191404113974.png/1000x1000bb.jpg",
  "link": "https://youtube.com/watch?v=YQHsXMglC9A",
  "lyrics": "Hello, it's me\nI was wondering if after all these years you'd like to meet\nTo go over everything\nThey say that time's supposed to heal ya, but I ain't done much healing\n\nHello, can you hear me?\nI'm in California dreaming about who we used to be\nWhen we were younger and free\nI've forgotten how it felt before the world fell at our feet\n\nThere's such a difference between us\nAnd a million miles\n\nHello from the other side\n\nI must've called a thousand times\nTo tell you I'm sorry for everything that I've done\nBut when I call, you never seem to be home\n\nHello from the outside\nAt least I can say that I've tried\nTo tell you I'm sorry for breaking your heart\nBut it don't matter, it clearly doesn't tear you apart anymore\n\nHello, how are you?\nIt's so typical of me to talk about myself, I'm sorry\nI hope that you're well\nDid you ever make it out of that town where nothing ever happened?\n\nIt's no secret that the both of us\nAre running out of time\n\nSo hello from the other side (other side)\nI must've called a thousand times (thousand times)\nTo tell you I'm sorry for everything that I've done\nBut when I call, you never seem to be home\n\nHello from the outside (outside)\nAt least I can say that I've tried (I've tried)\nTo tell you I'm sorry for breaking your heart\nBut it don't matter, it clearly doesn't tear you apart anymore\n\nOoh (lows, lows, lows, lows), anymore\n(Highs, highs, highs, highs)\nOoh (lows, lows, lows, lows), anymore\n(Highs, highs, highs, highs)\nOoh (lows, lows, lows, lows), anymore\n(Highs, highs, highs, highs)\nAnymore (lows, lows, lows, lows)\n\nHello from the other side (other side)\nI must've called a thousand times (thousand times)\nTo tell you I'm sorry for everything that I've done\nBut when I call, you never seem to be home\n\nHello from the outside (outside)\nAt least I can say that I've tried (I've tried)\nTo tell you I'm sorry for breaking your heart\n\nBut it don't matter, it clearly doesn't tear you apart anymore"
}
```
{% endswagger-response %}
{% endswagger %}

## Example

```javascript
const fetch = require("node-fetch")
const api_response = await fetch(`https://hunterapi.tk/api/lyrics?song=Hello`).then(r => r.json())
```

### Output

```json
{
  "success": true,
  "name": "Hello",
  "author": "Adele",
  "explicit": false,
  "release_date": "2015-10-23T07:00:00Z",
  "genre": "Pop",
  "length": "4:56",
  "thumbnail": "https://is5-ssl.mzstatic.com/image/thumb/Music116/v4/5a/47/6d/5a476ddd-4690-1297-1896-6a286a497a21/191404113974.png/1000x1000bb.jpg",
  "link": "https://youtube.com/watch?v=YQHsXMglC9A",
  "lyrics": "Hello, it's me\nI was wondering if after all these years you'd like to meet\nTo go over everything\nThey say that time's supposed to heal ya, but I ain't done much healing\n\nHello, can you hear me?\nI'm in California dreaming about who we used to be\nWhen we were younger and free\nI've forgotten how it felt before the world fell at our feet\n\nThere's such a difference between us\nAnd a million miles\n\nHello from the other side\n\nI must've called a thousand times\nTo tell you I'm sorry for everything that I've done\nBut when I call, you never seem to be home\n\nHello from the outside\nAt least I can say that I've tried\nTo tell you I'm sorry for breaking your heart\nBut it don't matter, it clearly doesn't tear you apart anymore\n\nHello, how are you?\nIt's so typical of me to talk about myself, I'm sorry\nI hope that you're well\nDid you ever make it out of that town where nothing ever happened?\n\nIt's no secret that the both of us\nAre running out of time\n\nSo hello from the other side (other side)\nI must've called a thousand times (thousand times)\nTo tell you I'm sorry for everything that I've done\nBut when I call, you never seem to be home\n\nHello from the outside (outside)\nAt least I can say that I've tried (I've tried)\nTo tell you I'm sorry for breaking your heart\nBut it don't matter, it clearly doesn't tear you apart anymore\n\nOoh (lows, lows, lows, lows), anymore\n(Highs, highs, highs, highs)\nOoh (lows, lows, lows, lows), anymore\n(Highs, highs, highs, highs)\nOoh (lows, lows, lows, lows), anymore\n(Highs, highs, highs, highs)\nAnymore (lows, lows, lows, lows)\n\nHello from the other side (other side)\nI must've called a thousand times (thousand times)\nTo tell you I'm sorry for everything that I've done\nBut when I call, you never seem to be home\n\nHello from the outside (outside)\nAt least I can say that I've tried (I've tried)\nTo tell you I'm sorry for breaking your heart\n\nBut it don't matter, it clearly doesn't tear you apart anymore"
}
```
