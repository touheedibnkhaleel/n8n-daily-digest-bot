# Daily Digest Bot (n8n)

An n8n workflow that sends a daily message to Discord with the
weather and the top 3 news headlines.

## Nodes used
Schedule Trigger, HTTP Request (Open-Meteo), RSS Read, Limit,
Code, Merge, Edit Fields, Discord

## How to use
1. In n8n, click ... > Import from File and select the JSON file.
2. Create your own Discord webhook credential.
3. Change the latitude/longitude in the HTTP Request node to your city.
4. Click Execute workflow.
