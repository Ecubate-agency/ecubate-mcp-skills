---
name: search-term-auditor
description: "Audit search term health for one client account — wasted spend, negative coverage, n-gram waste, close-variant drift, promotion candidates and PMax terms — and write a scored report to the client folder. Use for \"search term audit\", \"n-gram analysis\", \"negative keyword audit\", \"irrelevant search terms\", \"wasted spend\", \"which terms should we add or exclude\", \"SQR\". Read-only: it recommends, it never changes the account."
argument-hint: "<client> [module]"
---

This skill lives on the Ecubate connector, so it is always the latest version.

1. Call the Ecubate connector's `get_skill` with name `search-term-auditor` and follow what it returns as the procedure, exactly. Read its supporting files with `get_skill_file` and its references with `get_reference` when it points at them.
2. The request: $ARGUMENTS
3. Follow the connector's own instructions as well: read the client with `get_client` first, and save everything you produce with its save tools, which commit to the client folder for the team.

If the Ecubate connector is not connected, stop and tell the person to connect it: open the Ecubate plugin in Customize > Plugins, tab Connectors, and sign in with an @ecubate.com Google account (https://mcp.ecubate.com explains it).
