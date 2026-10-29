---
name: gmc-pre-launch-audit
description: "Audit a Shopify/ecommerce store for Google Merchant Center readiness BEFORE the GMC is created or the feed is connected, so the store passes Google's misrepresentation screening on the first try. Use this whenever the user wants to check a store before GMC, prepare a store for Google Shopping, run a compliance audit on a new brand, verify a store is \"GMC-ready\", pre-flight a dropshipping store, or asks anything like \"is this store ready for Google\", \"check [domain] before we make the GMC\", \"audit this store for misrep risk\", or \"onboard this client store for Google Ads/Shopping\". Also trigger when a previously suspended operator is building a fresh store/brand and wants to avoid a repeat. Covers website content, policies, business identity, payment/checkout consistency, feed data, trust signals, and account/identity setup hygiene."
---

This skill lives on the Ecubate connector, so it is always the latest version.

1. Call the Ecubate connector's `get_skill` with name `gmc-pre-launch-audit` and follow what it returns as the procedure, exactly. Read its supporting files with `get_skill_file` and its references with `get_reference` when it points at them.
2. The request: $ARGUMENTS
3. Follow the connector's own instructions as well: read the client with `get_client` first, and save everything you produce with its save tools, which commit to the client folder for the team.

If the Ecubate connector is not connected, stop and tell the person to connect it: open the Ecubate plugin in Customize > Plugins, tab Connectors, and sign in with an @ecubate.com Google account (https://mcp.ecubate.com explains it).
