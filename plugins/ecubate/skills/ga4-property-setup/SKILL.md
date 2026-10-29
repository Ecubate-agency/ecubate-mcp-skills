---
name: ga4-property-setup
description: "Audit a client's Google Analytics 4 property against Ecubate's configuration standard and propose the changes needed to close the gaps. Use this whenever the user wants to check whether GA4 is set up correctly, audit a GA4 property, review GA4 settings for a client, fix GA4 configuration, check data retention or consent or attribution settings, review which events and key events exist, verify the BigQuery or Google Ads link is present, or asks anything like \"is GA4 set up right for [client]\", \"audit the GA4 property\", \"what's wrong with our GA4\", \"why is GA4 revenue off\", \"check GA4 before we start reporting\", or \"set up GA4 for this webshop\". Also trigger when GA4 data looks incomplete or implausible, when explorations turn up empty, when traffic is attributed to a payment provider, or when onboarding a client reaches the GA4 task."
argument-hint: "<client>"
---

This skill lives on the Ecubate connector, so it is always the latest version.

1. Call the Ecubate connector's `get_skill` with name `ga4-property-setup` and follow what it returns as the procedure, exactly. Read its supporting files with `get_skill_file` and its references with `get_reference` when it points at them.
2. The request: $ARGUMENTS
3. Follow the connector's own instructions as well: read the client with `get_client` first, and save everything you produce with its save tools, which commit to the client folder for the team.

If the Ecubate connector is not connected, stop and tell the person to connect it: open the Ecubate plugin in Customize > Plugins, tab Connectors, and sign in with an @ecubate.com Google account (https://mcp.ecubate.com explains it).
