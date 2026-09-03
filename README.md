# GDPR Account Auditor — public site

The homepage, privacy policy and terms of service for the GDPR Account
Auditor, served via GitHub Pages.

These pages exist because Google requires an application home page and a
public privacy policy link before an OAuth app can leave "Testing" status.
The URLs are referenced from the Google Auth Platform **Branding** page.

| Page | Purpose |
|---|---|
| `index.html` | Application home page |
| `privacy.html` | Privacy policy — every claim verified against the application source |
| `terms.html` | Terms of service |

Plain static HTML with one stylesheet. No build step and no external
resources, so the pages keep working for as long as the OAuth client
points at them.

## Deploying

Settings → Pages → Deploy from a branch → `main` / root.
