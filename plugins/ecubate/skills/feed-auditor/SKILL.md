---
name: feed-auditor
description: "Audit the product feed of one client account — disapprovals, Google's issue list by cause with resolution text, out-of-stock spend, descriptions, images, GTINs, titles, and eligible products no campaign advertises. Use for \"feed audit\", \"afgekeurde producten\", \"product disapprovals\", \"feed gezondheid\", \"out of stock\", \"producten niet zichtbaar\", \"Merchant Center feed\". Read-only: it reports, it never changes the feed or the account."
argument-hint: "<client> [account]"
---

This skill lives on the Ecubate connector, so it is always the latest version.

1. Call the Ecubate connector's `get_skill` with name `feed-auditor` and follow what it returns as the procedure, exactly. Read its supporting files with `get_skill_file` and its references with `get_reference` when it points at them.
2. The request: $ARGUMENTS
3. Follow the connector's own instructions as well: read the client with `get_client` first, and save everything you produce with its save tools, which commit to the client folder for the team.

If the Ecubate connector is not connected, stop and tell the person to connect it: open the Ecubate plugin in Customize > Plugins, tab Connectors, and sign in with an @ecubate.com Google account (https://mcp.ecubate.com explains it).
