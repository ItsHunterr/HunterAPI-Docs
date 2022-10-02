---
description: Get information from a discord application.
---

# 🤖 Discord Application

## Making the request

****[**https://hunterapi.tk/api/discord/application**](https://hunterapi.tk/api/discord/application)****

{% swagger method="get" path="/discord/application" baseUrl="https://hunterapi.tk/api" summary="Get information from a discord application" %}
{% swagger-description %}

{% endswagger-description %}

{% swagger-parameter in="query" name="id" type="String" required="true" %}
The ID of the application
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="" %}
```json
{
  "id": "908749764428955738",
  "name": "Hubi",
  "description": "Hi! Im **Hubi**\n<:arrowwhite:979534765445230652> Discord multipurpose bot. Minecraft, Valorant, Rocket League, Moderation, Fun, Info and many more commands! \n\n<:__:969699287929868358> Website: https://hubi.sytes.net/",
  "tags": [
    "gaming",
    "moderation",
    "multipurpose",
    "utility"
  ],
  "avatar_png": "https://cdn.discordapp.com/avatars/908749764428955738/fc0952cbc1db2d1b22e9c413a5791a81.png?size=4096",
  "avatar_jpg": "https://cdn.discordapp.com/avatars/908749764428955738/fc0952cbc1db2d1b22e9c413a5791a81.jpg?size=4096",
  "scopes": [
    "bot",
    "applications.commands"
  ],
  "permissions": "1377010310262",
  "bot_public": true,
  "bot_require_code_grant": false,
  "intents": [
    "GATEWAY_PRESENCE_LIMITED",
    "GATEWAY_GUILD_MEMBERS_LIMITED",
    "GATEWAY_MESSAGE_CONTENT_LIMITED"
  ],
  "badges": [
    "APPLICATION_COMMAND_BADGE"
  ],
  "other_flags": []
}
```
{% endswagger-response %}
{% endswagger %}

## Example

```javascript
const fetch = require("node-fetch")
const api_response = await fetch(`https://hunterapi.tk/api/discord/application?id=908749764428955738`).then(r => r.json())
```

### Output

```json
{
  "id": "908749764428955738",
  "name": "Hubi",
  "description": "Hi! Im **Hubi**\n<:arrowwhite:979534765445230652> Discord multipurpose bot. Minecraft, Valorant, Rocket League, Moderation, Fun, Info and many more commands! \n\n<:__:969699287929868358> Website: https://hubi.sytes.net/",
  "tags": [
    "gaming",
    "moderation",
    "multipurpose",
    "utility"
  ],
  "avatar_png": "https://cdn.discordapp.com/avatars/908749764428955738/fc0952cbc1db2d1b22e9c413a5791a81.png?size=4096",
  "avatar_jpg": "https://cdn.discordapp.com/avatars/908749764428955738/fc0952cbc1db2d1b22e9c413a5791a81.jpg?size=4096",
  "scopes": [
    "bot",
    "applications.commands"
  ],
  "permissions": "1377010310262",
  "bot_public": true,
  "bot_require_code_grant": false,
  "intents": [
    "GATEWAY_PRESENCE_LIMITED",
    "GATEWAY_GUILD_MEMBERS_LIMITED",
    "GATEWAY_MESSAGE_CONTENT_LIMITED"
  ],
  "badges": [
    "APPLICATION_COMMAND_BADGE"
  ],
  "other_flags": []
}
```
