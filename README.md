[![LinkedIn Profile][badge_linkedin]][link_linkedin]
[![Link Mastodon][badge_mastodon]][link_mastodon]
[![Follow on Twitter][badge_twitter]][link_twitter]
[![Check my blog][badge_blog]][link_blog]

# Home Assistant + Microsoft = awesomeness
A listing of Home Assistant integrations with Microsoft technologies, and solutions using them.

Know of one that isn't listed? Just submit a PR to get it added.


# Native Integrations
https://www.home-assistant.io/integrations/#search/microsoft


# Custom Components (HACS)
## Microsoft Graph
[Office 365 Integration for Home Assistant](https://github.com/RogerSelwyn/O365-HomeAssistant) (moving towards EOL)
[Microsoft 365 Calendar Integration for Home Assistant](https://github.com/RogerSelwyn/MS365-Calendar)
[Microsoft 365 Mail Integration for Home Assistant](https://github.com/RogerSelwyn/MS365-Mail)
[Microsoft 365 Teams Integration for Home Assistant](https://github.com/RogerSelwyn/MS365-Teams)
[Microsoft 365 To Do Integration for Home Assistant](https://github.com/RogerSelwyn/MS365-ToDo)

[Detects the authorized user's Microsoft Teams availability](https://github.com/geoffreylagaisse/Hass-Microsoft-Graph)

[Brings your Microsoft To Do tasks into Home Assistant and allows creating new tasks](https://github.com/black-roland/homeassistant-microsoft-todo)

[Microsoft Teams Presence Status to MQTT Server to Home Assistant to LED Cube](https://github.com/ultrara1n/teams-presence-mqtt)



## NOT Microsoft Graph
[Microsoft Edge TTS for Home Assistant](https://github.com/hasscc/hass-edge-tts)

[A .NET console application that will update entities in Home Assistant based on Microsoft Teams status](https://github.com/pathartl/TeamsPresence)

[Microsoft Text-to-Speech that changes options dynamically](https://github.com/realthk/microsoft_tts)

[Azure OpenAI Conversation for Home Assistant](https://github.com/joselcaguilar/azure-openai-ha)



# Solutions
These are either built on top of Custom Components, or don't require them at all.
## Microsoft Graph
[Raise your desk automatically when in a Teams call or meeting](https://github.com/loryanstrant/HA-ESPHome-TeamsDesk)



## NOT Microsoft Graph 
[Monitor your Teams presence updates and push them to Home Assistant](https://github.com/Rookeh/ha-teams-watcher)

[A simple command line application that connects to the local Teams API and forwards the meeting status to any endpoint](https://github.com/svrooij/teams-monitor)

[Send and receive Teams Meetings events to an MQTT Broker](https://github.com/MrRoundRobin/TeamsMqttBridge)

[Displaying multiple Fitbit accounts in Home Assistant using Azure Logic Apps](https://www.loryanstrant.com/2023/02/12/displaying-multiple-fitbit-accounts-in-home-assistant-using-azure-logic-apps/)


[badge_blog]: https://img.shields.io/badge/www.loryanstrant.com-blue?style=for-the-badge
[badge_linkedin]: https://img.shields.io/badge/LinkedIn-loryanstrant-blue?style=for-the-badge&logo=linkedin
[badge_mastodon]: https://img.shields.io/mastodon/follow/109262349065015855?domain=https%3A%2F%2Fmastodon.online&label=%40loryanstrant%40mastodon.online&logo=mastodon&logoColor=white&style=for-the-badge
[badge_twitter]: https://img.shields.io/twitter/follow/loryanstrant?logo=twitter&style=for-the-badge
[link_blog]: https://www.loryanstrant.com
[link_linkedin]: https://www.linkedin.com/in/loryanstrant
[link_mastodon]: https://mastodon.online/@LoryanStrant
[link_twitter]: https://twitter.com/LoryanStrant
