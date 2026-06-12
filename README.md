# muud-campaigns-host

Temporary static host for MUUD Health email campaign HTML.

**Why this exists:** Zoho Campaigns API requires a publicly-fetchable `content_url` to create campaigns. Files here are served via GitHub Pages so Zoho's unauthenticated fetcher can pull them.

**Lifecycle:** Will be deleted once `platform.muudhealth.com/email/` is the canonical host.

Campaign HTML files only — no secrets, no source code.
