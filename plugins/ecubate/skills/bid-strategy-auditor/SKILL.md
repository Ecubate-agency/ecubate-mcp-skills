---
name: bid-strategy-auditor
description: "Audit the bid strategies of one client account — which campaigns run without smart bidding, which have no target, which targets are not being met, what each one is really delivering on sales, and which campaigns still bid manually on a max CPC nobody has touched since Google removed Enhanced CPC in March 2025. Use for \"bid strategy audit\", \"biedstrategie\", \"tROAS\", \"tCPA\", \"smart bidding\", \"target te hoog\", \"welke campagnes hebben geen doel\", \"handmatig bieden\", \"ECPC\", \"manual CPC\". Read-only: it proposes, it never changes the account."
argument-hint: "<client> [account]"
---

This skill lives on the Ecubate connector, so it is always the latest version.

1. Call the Ecubate connector's `get_skill` with name `bid-strategy-auditor` and follow what it returns as the procedure, exactly. Read its supporting files with `get_skill_file` and its references with `get_reference` when it points at them.
2. The request: $ARGUMENTS
3. Follow the connector's own instructions as well: read the client with `get_client` first, and save everything you produce with its save tools, which commit to the client folder for the team.

If the Ecubate connector is not connected, stop and tell the person to connect it: open the Ecubate plugin in Customize > Plugins, tab Connectors, and sign in with an @ecubate.com Google account (https://mcp.ecubate.com explains it).
