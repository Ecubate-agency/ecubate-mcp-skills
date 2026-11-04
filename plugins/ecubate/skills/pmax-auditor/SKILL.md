---
name: pmax-auditor
description: "Audit the Performance Max campaigns of one client account — asset-group structure and composition, per-asset performance, audience signals, brand defense, NCA/lifecycle settings, channel mix as a symptom, URL expansion, and the feed link — scored per campaign, written to the client folder. Use for \"pmax audit\", \"performance max audit\", \"asset groups\", \"audience signals\", \"brand exclusion\", \"brand uitsluiten in PMax\", \"NCA\", \"new customer acquisition\", \"URL expansion\", \"kanaalverdeling PMax\", \"PMax structuur\". Read-only: it recommends, it never changes the account."
argument-hint: "<client> [account]"
---

This skill lives on the Ecubate connector, so it is always the latest version.

1. Call the Ecubate connector's `get_skill` with name `pmax-auditor` and follow what it returns as the procedure, exactly. Read its supporting files with `get_skill_file` and its references with `get_reference` when it points at them.
2. Apply the procedure to the user's request and any arguments supplied with the skill. Follow the returned PLUGIN_MAP to translate source paths and tools to this host.
3. Follow the connector's own instructions as well: read the client with `get_client` first, and save everything you produce with its save tools, which commit to the client folder for the team.

If the Ecubate tools are unavailable, stop and report which tools are missing. Ask the person to connect the Ecubate MCP in their host and sign in with their own @ecubate.com Google account. Never substitute local procedures or another person's credentials. https://mcp.ecubate.com explains the connection.
