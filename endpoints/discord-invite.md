---
description: Get information from a discord invite.
---

# 📩 Discord Invite

## Making the request

****[**https://hunterapi.tk/api/discord/invite**](https://hunterapi.tk/api/discord/invite)****

{% swagger method="get" path="/discord/invite" baseUrl="https://hunterapi.tk/api" summary="Get information from a discord invite" %}
{% swagger-description %}

{% endswagger-description %}

{% swagger-parameter in="query" name="url" type="String" required="true" %}
The URL of the discord invite
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="" %}
```json
{
  "invite": "https://discord.com/invite/qX7MpVEJFj ",
  "expires": "Cannot obtain date or invitation is unlimited.",
  "guild_id": "908428491484196955",
  "guild_name": "The Hub",
  "guild_description": "Joining the server you will get the latest hubi bot news and learn more about my API and my websites.",
  "guild_icon": "https://cdn.discordapp.com/icons/908428491484196955/359ec7e43cb9ed28cf9b9ac0ac213f7b?size=64",
  "channel_name": "・✅・verify",
  "channel_id": "909160040211042374",
  "inviter_name": "Hunterr#0040",
  "inviter_id": "522980853320515594"
}
```
{% endswagger-response %}
{% endswagger %}

## Example

```javascript
const fetch = require("node-fetch")
const api_response = await fetch(`https://hunterapi.tk/api/discord/invite?url=https://discord.gg/qX7MpVEJFj`).then(r => r.json())
```

### Output

```json
{
  "invite": "https://discord.com/invite/qX7MpVEJFj ",
  "expires": "Cannot obtain date or invitation is unlimited.",
  "guild_id": "908428491484196955",
  "guild_name": "The Hub",
  "guild_description": "Joining the server you will get the latest hubi bot news and learn more about my API and my websites.",
  "guild_icon": "https://cdn.discordapp.com/icons/908428491484196955/359ec7e43cb9ed28cf9b9ac0ac213f7b?size=64",
  "channel_name": "・✅・verify",
  "channel_id": "909160040211042374",
  "inviter_name": "Hunterr#0040",
  "inviter_id": "522980853320515594"
}
```

