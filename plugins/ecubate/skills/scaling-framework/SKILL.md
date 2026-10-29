---
name: scaling-framework
description: "Plot one client account on the Ecubate Scaling Framework — read the live SOP from the Company Wiki, walk the quick scan and the gates per market, and report which stage the account is at, what the Account Lead still has to confirm, and the next builds that break through to the next stage. Use for \"plot dit account\", \"waar staat deze klant op het scaling framework\", \"welke stage\", \"scaling framework\", \"stage bepalen\", \"wat is de volgende stap voor deze klant\", \"re-plot\", \"90-day results call voorbereiden\". The framework itself is edited in Notion, never here. Read-only: it plots and proposes, it never changes the account."
argument-hint: "<client> [account]"
---

This skill lives on the Ecubate connector, so it is always the latest version.

1. Call the Ecubate connector's `get_skill` with name `scaling-framework` and follow what it returns as the procedure, exactly. Read its supporting files with `get_skill_file` and its references with `get_reference` when it points at them.
2. The request: $ARGUMENTS
3. Follow the connector's own instructions as well: read the client with `get_client` first, and save everything you produce with its save tools, which commit to the client folder for the team.

If the Ecubate connector is not connected, stop and tell the person to connect it: open the Ecubate plugin in Customize > Plugins, tab Connectors, and sign in with an @ecubate.com Google account (https://mcp.ecubate.com explains it).
