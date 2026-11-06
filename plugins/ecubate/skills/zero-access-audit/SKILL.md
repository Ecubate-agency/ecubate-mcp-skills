---
name: zero-access-audit
description: "For PROSPECTS without access, never for clients or leads that gave access. Read a brand's Google Ads from the outside, from its domain alone, in its main ad market and only from what Google labels Sponsored: who buys ads on its name, its text ads line by line, its Shopping ads and titles against the tiles beside them, its closest competitor, its YouTube video ads with views and landing pages, and its Meta ads beside Google. Delivers a short Ecubate deck the prospect replies to, with quick wins, five questions only they can answer, a video script and an outreach sequence; every number recounted from saved page text and graded by a blind verifier. Use for \"zero-access audit\", \"audit this brand without access\", \"prospect scan\", \"quick scan zonder toegang\", \"scan dit merk\", \"outside-in scan\", \"wat zien shoppers van dit merk op Google\". Leads with access: /ecubate:lead-account-scan. Read-only, sends nothing."
argument-hint: "<brand domain> [market]"
---

This skill lives on the Ecubate connector, so it is always the latest version.

1. Call the Ecubate connector's `get_skill` with name `zero-access-audit` and follow what it returns as the procedure, exactly. Read its supporting files with `get_skill_file` and its references with `get_reference` when it points at them.
2. Apply the procedure to the user's request and any arguments supplied with the skill. Follow the returned PLUGIN_MAP to translate source paths and tools to this host.
3. Follow the connector's own instructions as well: read the client with `get_client` first, and save everything you produce with its save tools, which commit to the client folder for the team.

If the Ecubate tools are unavailable, stop and report which tools are missing. Ask the person to connect the Ecubate MCP in their host and sign in with their own @ecubate.com Google account. Never substitute local procedures or another person's credentials. https://mcp.ecubate.com explains the connection.
