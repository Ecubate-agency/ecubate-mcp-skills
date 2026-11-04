---
name: bid-strategy-auditor
description: "Audit the bid strategies of one client account — which campaigns run without smart bidding, which have no target, which targets are not being met, what each one is really delivering on sales, and which campaigns still bid manually on a max CPC nobody has touched since Google removed Enhanced CPC in March 2025. Use for \"bid strategy audit\", \"biedstrategie\", \"tROAS\", \"tCPA\", \"smart bidding\", \"target te hoog\", \"welke campagnes hebben geen doel\", \"handmatig bieden\", \"ECPC\", \"manual CPC\". Read-only: it proposes, it never changes the account."
argument-hint: "<client> [account]"
---

This skill lives on the Ecubate connector, so it is always the latest version.

1. Call the Ecubate connector's `get_skill` with name `bid-strategy-auditor` and follow what it returns as the procedure, exactly. Read its supporting files with `get_skill_file` and its references with `get_reference` when it points at them.
2. Apply the procedure to the user's request and any arguments supplied with the skill. Follow the returned PLUGIN_MAP to translate source paths and tools to this host.
3. Follow the connector's own instructions as well: read the client with `get_client` first, and save everything you produce with its save tools, which commit to the client folder for the team.

If the Ecubate tools are unavailable, stop and report which tools are missing. Ask the person to connect the Ecubate MCP in their host and sign in with their own @ecubate.com Google account. Never substitute local procedures or another person's credentials. https://mcp.ecubate.com explains the connection.
