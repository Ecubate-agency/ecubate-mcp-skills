---
name: chatgpt-ads-builder
description: "Build the ChatGPT Ads campaigns for one client from what already works in their Google Ads — always two of them. A chat-card campaign takes the converting search terms and products, clusters them into themes, and turns each theme into an ad group with context hints, a landing page, a chat card and its image. A product feed campaign takes the client's feed in the ad account and splits it into one ad group per product-performance label value, each with a product-ad template. Asks budget, end date, objective, bid strategy and max CPC, shows the whole chain for approval, then creates it paused over the Advertiser API. Use for \"chatgpt ads\", \"openai ads\", \"bouw een chatgpt campagne\", \"adverteren in chatgpt\", \"chatgpt ads opzetten\", \"campagne in chatgpt\", \"chat card\", \"chatgpt shopping\", \"feed campagne\", \"product feed campagne\". Creates nothing until you approve, and everything it creates starts paused."
argument-hint: "<client> [market]"
---

This skill lives on the Ecubate connector, so it is always the latest version.

1. Call the Ecubate connector's `get_skill` with name `chatgpt-ads-builder` and follow what it returns as the procedure, exactly. Read its supporting files with `get_skill_file` and its references with `get_reference` when it points at them.
2. Apply the procedure to the user's request and any arguments supplied with the skill. Follow the returned PLUGIN_MAP to translate source paths and tools to this host.
3. Follow the connector's own instructions as well: read the client with `get_client` first, and save everything you produce with its save tools, which commit to the client folder for the team.

If the Ecubate tools are unavailable, stop and report which tools are missing. Ask the person to connect the Ecubate MCP in their host and sign in with their own @ecubate.com Google account. Never substitute local procedures or another person's credentials. https://mcp.ecubate.com explains the connection.
