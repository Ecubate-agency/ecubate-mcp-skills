---
name: performance-diagnostic
description: "Diagnose what changed in one client account over the last 7, 14, 30 or 45 days against the period before it, and produce the changes to make. Reports how much revenue moved in money, which segment carries it (search vs shopping vs PMax, brand vs non-brand), which campaign moved most and why (budget cap, auction rank, click price, conversion rate, order value, demand, eligible inventory), what the change history explains including keyword pauses Google records without a name, and whether the drop is real or orders still coming in. Writes an HTML report in plain language (what happened, what changed, what we propose) and an action CSV for /ecubate:push-to-gads, hands budget and bid-target sizing to the owning skills as build-queue briefs, and publishes the HTML as a shareable link."
argument-hint: "<client> [account] [--window 7|14|30]"
---

This skill lives on the Ecubate connector, so it is always the latest version.

1. Call the Ecubate connector's `get_skill` with name `performance-diagnostic` and follow what it returns as the procedure, exactly. Read its supporting files with `get_skill_file` and its references with `get_reference` when it points at them.
2. The request: $ARGUMENTS
3. Follow the connector's own instructions as well: read the client with `get_client` first, and save everything you produce with its save tools, which commit to the client folder for the team.

If the Ecubate connector is not connected, stop and tell the person to connect it: open the Ecubate plugin in Customize > Plugins, tab Connectors, and sign in with an @ecubate.com Google account (https://mcp.ecubate.com explains it).
