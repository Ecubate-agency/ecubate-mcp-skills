---
name: keyword-research
description: "One-time keyword research when an account is onboarded — read the feed and the site for one client account, build the three-tier seed set, verify every keyword against real products, enrich with DataForSEO volume, discovery and search intent, diff against every keyword the account already runs, write ONE gap CSV plus the report, then cluster the gaps by the Single Ad Test and map them onto existing campaigns and ad groups — or propose new ones when the account has no structure yet. Use for \"keyword research\", \"keyword onderzoek\", \"zoekwoordenonderzoek\", \"seed keywords\", \"keyword lijst bouwen\", \"welke keywords missen we\", \"onboarding keywords\", \"nieuwe keywords voor\". Read-only: it reports gaps, it proposes nothing and never changes the account."
argument-hint: "<client> [account]"
---

This skill lives on the Ecubate connector, so it is always the latest version.

1. Call the Ecubate connector's `get_skill` with name `keyword-research` and follow what it returns as the procedure, exactly. Read its supporting files with `get_skill_file` and its references with `get_reference` when it points at them.
2. Apply the procedure to the user's request and any arguments supplied with the skill. Follow the returned PLUGIN_MAP to translate source paths and tools to this host.
3. Follow the connector's own instructions as well: read the client with `get_client` first, and save everything you produce with its save tools, which commit to the client folder for the team.

If the Ecubate tools are unavailable, stop and report which tools are missing. Ask the person to connect the Ecubate MCP in their host and sign in with their own @ecubate.com Google account. Never substitute local procedures or another person's credentials. https://mcp.ecubate.com explains the connection.
