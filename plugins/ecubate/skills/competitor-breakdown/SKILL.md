---
name: competitor-breakdown
description: "Deep dive on one competitor, or the top 3 from the landscape's shortlist - every ad they run on Google and Meta, where each one lands (product pages, category pages, listicles, advertorials, quizzes, Meta Instant Experiences), what those pages sell with, and the full funnel from ad to product page - laid against the client's own funnel read the same way, ending in a numbered list of what we change, each with theirs against ours and who acts on it. Reads everything through the agency servers - the Meta Ad Library (every active ad with its link, in Meta's own impression order), the Ads Transparency Center with the winning previews read for headline, display path, sitelinks and seller rating, every landing page through DataForSEO, and our own final URLs, cost and ad groups through the Google Ads API. Writes one HTML page whose first screen is the verdict, what we change and the two funnels in one line each, a client version, briefs for the changes, and the run in profile/competitors.json."
argument-hint: "<client> [competitor domain, or blank for the landscape shortlist]"
---

This skill lives on the Ecubate connector, so it is always the latest version.

1. Call the Ecubate connector's `get_skill` with name `competitor-breakdown` and follow what it returns as the procedure, exactly. Read its supporting files with `get_skill_file` and its references with `get_reference` when it points at them.
2. The request: $ARGUMENTS
3. Follow the connector's own instructions as well: read the client with `get_client` first, and save everything you produce with its save tools, which commit to the client folder for the team.

If the Ecubate connector is not connected, stop and tell the person to connect it: open the Ecubate plugin in Customize > Plugins, tab Connectors, and sign in with an @ecubate.com Google account (https://mcp.ecubate.com explains it).
