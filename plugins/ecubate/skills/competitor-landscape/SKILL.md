---
name: competitor-landscape
description: "Map a client's whole competitive field without being given a single competitor name, and answer six things about every competitor that matters - why they are a competitor, how much they overlap with us (on the Google Shopping shelf as Merchant Center measures it, and in search), where they sit biggest to smallest, reseller or own brand, their tone of voice, and what they do that we don't. Finds the field itself from the agency servers - Merchant Center's competition reports (who shares our Shopping pages and sits above us, the biggest merchants on the shelf, our visibility against the category, our price position), Auction Insights, a SERP sweep on the client's own keywords, DataForSEO Labs, the Ads Transparency Center and the Meta Ad Library - reads the client through the same sources so every gap is a like-for-like diff, and routes each gap to whoever can act on it. Wide and shallow by design - it picks the 1-3 competitors worth a deep dive and hands them to the breakdown; it does not walk their funnel."
argument-hint: "<client> [market]"
---

This skill lives on the Ecubate connector, so it is always the latest version.

1. Call the Ecubate connector's `get_skill` with name `competitor-landscape` and follow what it returns as the procedure, exactly. Read its supporting files with `get_skill_file` and its references with `get_reference` when it points at them.
2. The request: $ARGUMENTS
3. Follow the connector's own instructions as well: read the client with `get_client` first, and save everything you produce with its save tools, which commit to the client folder for the team.

If the Ecubate connector is not connected, stop and tell the person to connect it: open the Ecubate plugin in Customize > Plugins, tab Connectors, and sign in with an @ecubate.com Google account (https://mcp.ecubate.com explains it).
