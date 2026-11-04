---
name: account-health-monitor
description: "Explain the health sweep's findings for one client account — what stalled, what stopped measuring, which URLs are broken, what moved against the account's own baseline, and what to do next. Use for \"account health\", \"gezondheid van het account\", \"waarom kreeg ik een melding\", \"staat het account stil\", \"meting kapot\", \"kapotte URLs\", \"welke accounts staan op rood\". Read-only: it explains and proposes, it never changes the account."
argument-hint: "<client> [account] [--recheck] [--http]"
---

This skill lives on the Ecubate connector, so it is always the latest version.

1. Call the Ecubate connector's `get_skill` with name `account-health-monitor` and follow what it returns as the procedure, exactly. Read its supporting files with `get_skill_file` and its references with `get_reference` when it points at them.
2. Apply the procedure to the user's request and any arguments supplied with the skill. Follow the returned PLUGIN_MAP to translate source paths and tools to this host.
3. Follow the connector's own instructions as well: read the client with `get_client` first, and save everything you produce with its save tools, which commit to the client folder for the team.

If the Ecubate tools are unavailable, stop and report which tools are missing. Ask the person to connect the Ecubate MCP in their host and sign in with their own @ecubate.com Google account. Never substitute local procedures or another person's credentials. https://mcp.ecubate.com explains the connection.
