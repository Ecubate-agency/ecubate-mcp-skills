---
name: ad-auditor
description: "Audit the ads of one client account against the Ecubate ad standard, sheet first — the ad assets script sheet compared with the live account and the website: template integrity, customizer coverage, seasonal and scheduled assets (start and end dates respected), extension coverage per campaign (sitelinks, callouts, snippets, business name and logo), claims checked against the live site, and ad-group performance behind data gates. Use for \"ad audit\", \"advertentie audit\", \"RSA check\", \"advertenties controleren\", \"sitelinks\", \"extensies\", \"verlopen acties\", \"Black Friday assets\", \"welke ad groups presteren slecht\", \"ad copy\". It proposes a numbered step table; it changes the account or the sheet only for the steps a person approves."
argument-hint: "<client> [account] [market]"
---

This skill lives on the Ecubate connector, so it is always the latest version.

1. Call the Ecubate connector's `get_skill` with name `ad-auditor` and follow what it returns as the procedure, exactly. Read its supporting files with `get_skill_file` and its references with `get_reference` when it points at them.
2. Apply the procedure to the user's request and any arguments supplied with the skill. Follow the returned PLUGIN_MAP to translate source paths and tools to this host.
3. Follow the connector's own instructions as well: read the client with `get_client` first, and save everything you produce with its save tools, which commit to the client folder for the team.

If the Ecubate tools are unavailable, stop and report which tools are missing. Ask the person to connect the Ecubate MCP in their host and sign in with their own @ecubate.com Google account. Never substitute local procedures or another person's credentials. https://mcp.ecubate.com explains the connection.
