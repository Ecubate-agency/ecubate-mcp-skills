---
name: lead-account-scan
description: "For LEADS only, never for existing clients. Scan a lead's Google Ads, Merchant Center, GTM and GA4 once we have access, and deliver a client-ready slide deck in the Ecubate brand book: the account set against the Ecubate Blueprint task by task, as a decision tree that says where to start, with the budget leak in euros and each market on the Scaling Framework. Measures against the lead's own account (no target needed) and pulls everything live, never from a snapshot. First a full audit spreadsheet (a copy of the Drive template) with every check, its finding, how we fix it according to the Blueprint and the impact; the deck is the selection of what weighs most. Use for \"lead scan\", \"quick scan voor een lead\", \"scan dit account van een lead\", \"we hebben toegang gekregen tot\", \"waar lekt hun budget\", \"maak een quick scan deck\", \"plot deze lead\". Existing clients get the auditors and /ecubate:performance-diagnostic instead; outside-in scans without access are prospect-quick-scan. Read-only."
---

This skill lives on the Ecubate connector, so it is always the latest version.

1. Call the Ecubate connector's `get_skill` with name `lead-account-scan` and follow what it returns as the procedure, exactly. Read its supporting files with `get_skill_file` and its references with `get_reference` when it points at them.
2. The request: $ARGUMENTS
3. Follow the connector's own instructions as well: read the client with `get_client` first, and save everything you produce with its save tools, which commit to the client folder for the team.

If the Ecubate connector is not connected, stop and tell the person to connect it: open the Ecubate plugin in Customize > Plugins, tab Connectors, and sign in with an @ecubate.com Google account (https://mcp.ecubate.com explains it).
