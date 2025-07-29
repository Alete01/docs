---
sidebar_position: 5
title: "Google PSE"
---

:::warning
This tutorial is a community contribution and is not supported by the Open WebUI team. It serves only as a demonstration on how to customize Open WebUI for your specific use case. Want to contribute? Check out the contributing tutorial.
:::

## Google PSE API

### Setup

1. Go to Google Developers, use [Programmable Search Engine](https://developers.google.com/custom-search), and log on or create account.
2. Go to [control panel](https://programmablesearchengine.google.com/controlpanel/all) and click `Add` button
3. Enter a search engine name, set the other properties to suit your needs, verify you're not a robot and click `Create` button.
4. Get the `Search engine ID`. (Available after the engine is created)
5. To generate a Google Custom Search API Key access the Google Cloud Console and either select an existing project or create a new one.
6. Navigate to "APIs & Services" and then "Library." Search for and enable the "Custom Search API."
7. Go to "APIs & Services" and then "Credentials." Click on "Create credentials" and select "API key." A new API key will be generated.
8. Copy the generated API key and store it securely. For enhanced security, it is recommended to restrict the API key to only allow access to the "Custom Search API." This can be done by editing the API key's settings in the Credentials section and selecting "Restrict key" under "API restrictions," then choosing "Custom Search API."
9. With `API key` and `Search engine ID`, open `Open WebUI Admin panel` and click `Settings` tab, and then click `Web Search`
10. Enable `Web search` and Set `Web Search Engine` to `google_pse`
11. Fill `Google PSE API Key` with the `API key` and `Google PSE Engine Id` (# 4)
12. Click `Save`

![Open WebUI Admin panel](/images/tutorial_google_pse1.png)

#### Note

You have to enable `Web search` in the prompt field, using plus (`+`) button.
Search the web ;-)

![enable Web search](/images/tutorial_google_pse2.png)
