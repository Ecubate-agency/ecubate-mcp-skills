---
name: account-structure-auditor
description: "Audit how one client account is built and configured against the Ecubate standard — the AI Max norm with mandatory brand controls, the competitor exclusion and assortment inclusion on the campaigns that need them, the campaign-settings norms (networks, geo, languages, rotation, schedules, devices, caps, audiences), the naming template, brand separation, keyword overlap, duplicate keywords and SKAG fragmentation, auto-apply and auto-tagging. Brand LISTS themselves belong to /ecubate:audiences; this audit owns the campaign side and creates no list. Use for \"account audit\", \"structuur audit\", \"account structuur\", \"instellingen check\", \"AI Max\", \"brand controls\", \"merklijst aanhangen\", \"concurrenten uitsluiten\", \"assortiment inclusion\", \"search partners\", \"naamgeving campagnes\", \"campagne-instellingen\", \"SKAG\", \"auto-apply\". Read-only: it proposes, it never changes the account."
argument-hint: "<client> [account]"
---

This skill lives on the Ecubate connector, so it is always the latest version.

1. Call the Ecubate connector's `get_skill` with name `account-structure-auditor` and follow what it returns as the procedure, exactly. Read its supporting files with `get_skill_file` and its references with `get_reference` when it points at them.
2. Apply the procedure to the user's request and any arguments supplied with the skill. Follow the returned PLUGIN_MAP to translate source paths and tools to this host.
3. Follow the connector's own instructions as well: read the client with `get_client` first, and save everything you produce with its save tools, which commit to the client folder for the team.

If the Ecubate tools are unavailable, stop and report which tools are missing. Ask the person to connect the Ecubate MCP in their host and sign in with their own @ecubate.com Google account. Never substitute local procedures or another person's credentials. https://mcp.ecubate.com explains the connection.
