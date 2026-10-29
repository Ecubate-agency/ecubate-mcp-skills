---
name: unit-economics
description: "Work out what a client actually has to earn back — effective margin after order expenses and returns, break-even ROAS or CPA, and the target that follows from it — then verify it against the revenue basis the account really reports on and write it into the client record. Use for \"unit economics\", \"break-even uitrekenen\", \"break-even ROAS\", \"welk doel moeten we stellen\", \"target ROAS bepalen\", \"marge doorrekenen\", \"wat mag een lead kosten\", \"CPL berekenen\", \"klopt onze AOV\", \"zit er btw in de conversiewaarde\". Read-only on the account: it produces a number, it never changes a campaign."
argument-hint: "<client> [account]"
---

This skill lives on the Ecubate connector, so it is always the latest version.

1. Call the Ecubate connector's `get_skill` with name `unit-economics` and follow what it returns as the procedure, exactly. Read its supporting files with `get_skill_file` and its references with `get_reference` when it points at them.
2. The request: $ARGUMENTS
3. Follow the connector's own instructions as well: read the client with `get_client` first, and save everything you produce with its save tools, which commit to the client folder for the team.

If the Ecubate connector is not connected, stop and tell the person to connect it: open the Ecubate plugin in Customize > Plugins, tab Connectors, and sign in with an @ecubate.com Google account (https://mcp.ecubate.com explains it).
