---
name: push-to-gads
description: "Apply an approved change set to a live Google Ads account — negatives, keywords, budgets, bid strategies, conversion actions and goals, whatever an audit proposed. Reads a proposal file from the client folder, validates it against Google, asks, then applies. Use when someone asks to apply, push, execute or doorvoeren changes."
argument-hint: "<client> [proposal-file]"
---

This skill lives on the Ecubate connector, so it is always the latest version.

1. Call the Ecubate connector's `get_skill` with name `push-to-gads` and follow what it returns as the procedure, exactly. Read its supporting files with `get_skill_file` and its references with `get_reference` when it points at them.
2. Apply the procedure to the user's request and any arguments supplied with the skill. Follow the returned PLUGIN_MAP to translate source paths and tools to this host.
3. Follow the connector's own instructions as well: read the client with `get_client` first, and save everything you produce with its save tools, which commit to the client folder for the team.

If the Ecubate tools are unavailable, stop and report which tools are missing. Ask the person to connect the Ecubate MCP in their host and sign in with their own @ecubate.com Google account. Never substitute local procedures or another person's credentials. https://mcp.ecubate.com explains the connection.
