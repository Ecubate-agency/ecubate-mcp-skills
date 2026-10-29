---
name: pmax-auditor
description: "Audit the Performance Max campaigns of one client account — asset-group structure and composition, per-asset performance, audience signals, brand defense, NCA/lifecycle settings, channel mix as a symptom, URL expansion, and the feed link — scored per campaign, written to the client folder. Use for \"pmax audit\", \"performance max audit\", \"asset groups\", \"audience signals\", \"brand exclusion\", \"brand uitsluiten in PMax\", \"NCA\", \"new customer acquisition\", \"URL expansion\", \"kanaalverdeling PMax\", \"PMax structuur\". Read-only: it recommends, it never changes the account."
argument-hint: "<client> [account]"
---

This skill lives on the Ecubate connector, so it is always the latest version.

1. Call the Ecubate connector's `get_skill` with name `pmax-auditor` and follow what it returns as the procedure, exactly. Read its supporting files with `get_skill_file` and its references with `get_reference` when it points at them.
2. The request: $ARGUMENTS
3. Follow the connector's own instructions as well: read the client with `get_client` first, and save everything you produce with its save tools, which commit to the client folder for the team.

If the Ecubate connector is not connected, stop and tell the person to connect it: open the Ecubate plugin in Customize > Plugins, tab Connectors, and sign in with an @ecubate.com Google account (https://mcp.ecubate.com explains it).
