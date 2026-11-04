---
name: audiences
description: "Build and audit every account-level list the campaigns lean on — the three brand lists (own brand, competitors, assortment) built by API from the brands register, the negative keyword lists, the MCC and account negative placement lists for apps, display and YouTube, customer match with its real match rate, whether every list the account hangs is big enough for Google to serve against at all, the combined audience, and the attaching itself — brand inclusions and exclusions, the competitor exclusion, the assortment inclusion, the negative lists, and the remarketing lists this account has already established as observation ride-alongs — because a list that is built and never applied does nothing at all. This skill owns the brand lists end to end: creating them, filling them AND hanging them."
argument-hint: "<client> [account]"
---

This skill lives on the Ecubate connector, so it is always the latest version.

1. Call the Ecubate connector's `get_skill` with name `audiences` and follow what it returns as the procedure, exactly. Read its supporting files with `get_skill_file` and its references with `get_reference` when it points at them.
2. Apply the procedure to the user's request and any arguments supplied with the skill. Follow the returned PLUGIN_MAP to translate source paths and tools to this host.
3. Follow the connector's own instructions as well: read the client with `get_client` first, and save everything you produce with its save tools, which commit to the client folder for the team.

If the Ecubate tools are unavailable, stop and report which tools are missing. Ask the person to connect the Ecubate MCP in their host and sign in with their own @ecubate.com Google account. Never substitute local procedures or another person's credentials. https://mcp.ecubate.com explains the connection.
