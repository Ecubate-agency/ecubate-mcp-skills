---
name: keyword-research
description: "One-time keyword research when an account is onboarded — read the feed and the site for one client account, build the three-tier seed set, verify every keyword against real products, enrich with DataForSEO volume, discovery and search intent, diff against every keyword the account already runs, write ONE gap CSV plus the report, then cluster the gaps by the Single Ad Test and map them onto existing campaigns and ad groups — or propose new ones when the account has no structure yet. Use for \"keyword research\", \"keyword onderzoek\", \"zoekwoordenonderzoek\", \"seed keywords\", \"keyword lijst bouwen\", \"welke keywords missen we\", \"onboarding keywords\", \"nieuwe keywords voor\". Read-only: it reports gaps, it proposes nothing and never changes the account."
argument-hint: "<client> [account]"
---

This skill lives on the Ecubate connector, so it is always the latest version.

1. Call the Ecubate connector's `get_skill` with name `keyword-research` and follow what it returns as the procedure, exactly. Read its supporting files with `get_skill_file` and its references with `get_reference` when it points at them.
2. The request: $ARGUMENTS
3. Follow the connector's own instructions as well: read the client with `get_client` first, and save everything you produce with its save tools, which commit to the client folder for the team.

If the Ecubate connector is not connected, stop and tell the person to connect it: open the Ecubate plugin in Customize > Plugins, tab Connectors, and sign in with an @ecubate.com Google account (https://mcp.ecubate.com explains it).
