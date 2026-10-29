---
name: meta-campaign-builder
description: "Build or restructure the Meta (Facebook and Instagram) campaigns of one client the Ecubate way. Reads the client's decisions and unit economics, checks the inputs (ad account, Page, Instagram, pixel, audiences, budget, landing pages, assets from Drive), composes the Ecubate default structure (one ABO sales campaign with an evergreen video ad set and a catalog prospecting ad set, plus one catalog DPA campaign) with the client's own deviations marked, shows it as one table for approval, validates every write with Meta first, creates everything paused, reads it back with previews, activates only on an explicit yes, and records ids and decisions in the client folder. Also adds new ads, seasonal themes with ad-level schedules and budget schedules to an existing build. Use for \"bouw een Meta campagne\", \"meta ads opzetten\", \"facebook campagne\", \"instagram campagne\", \"nieuwe ads in meta\", \"thema ads toevoegen\", \"meta herstructureren\", \"build a Meta campaign\", \"restructure Meta\", \"new Meta ads\"."
argument-hint: "<client> [market]"
---

This skill lives on the Ecubate connector, so it is always the latest version.

1. Call the Ecubate connector's `get_skill` with name `meta-campaign-builder` and follow what it returns as the procedure, exactly. Read its supporting files with `get_skill_file` and its references with `get_reference` when it points at them.
2. The request: $ARGUMENTS
3. Follow the connector's own instructions as well: read the client with `get_client` first, and save everything you produce with its save tools, which commit to the client folder for the team.

If the Ecubate connector is not connected, stop and tell the person to connect it: open the Ecubate plugin in Customize > Plugins, tab Connectors, and sign in with an @ecubate.com Google account (https://mcp.ecubate.com explains it).
