---
name: account-changelog
description: "Report what changed in one client account over the last 30 days — who changed what, and which stored-state rewrites Google recorded without saying who or what. Use for \"account changelog\", \"wat is er gewijzigd\", \"change history\", \"wie heeft dit aangepast\", \"is er iets veranderd in dit account\", \"recente wijzigingen\", \"Editor sessie\". Read-only."
argument-hint: "<client> [account] [--days N]"
---

This skill lives on the Ecubate connector, so it is always the latest version.

1. Call the Ecubate connector's `get_skill` with name `account-changelog` and follow what it returns as the procedure, exactly. Read its supporting files with `get_skill_file` and its references with `get_reference` when it points at them.
2. Apply the procedure to the user's request and any arguments supplied with the skill. Follow the returned PLUGIN_MAP to translate source paths and tools to this host.
3. Follow the connector's own instructions as well: read the client with `get_client` first, and save everything you produce with its save tools, which commit to the client folder for the team.

If the Ecubate tools are unavailable, stop and report which tools are missing. Ask the person to connect the Ecubate MCP in their host and sign in with their own @ecubate.com Google account. Never substitute local procedures or another person's credentials. https://mcp.ecubate.com explains the connection.
