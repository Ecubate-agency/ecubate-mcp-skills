---
name: push-to-gads
description: "Apply an approved change set to a live Google Ads account — negatives, keywords, budgets, bid strategies, conversion actions and goals, whatever an audit proposed. Reads a proposal file from the client folder, validates it against Google, asks, then applies. Use when someone asks to apply, push, execute or doorvoeren changes."
argument-hint: "<client> [proposal-file]"
---

This skill lives on the Ecubate connector, so it is always the latest version.

1. Call the Ecubate connector's `get_skill` with name `push-to-gads` and follow what it returns as the procedure, exactly. Read its supporting files with `get_skill_file` and its references with `get_reference` when it points at them.
2. The request: $ARGUMENTS
3. Follow the connector's own instructions as well: read the client with `get_client` first, and save everything you produce with its save tools, which commit to the client folder for the team.

If the Ecubate connector is not connected, stop and tell the person to connect it: open the Ecubate plugin in Customize > Plugins, tab Connectors, and sign in with an @ecubate.com Google account (https://mcp.ecubate.com explains it).
