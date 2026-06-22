# Borderless Apps Site

Static site for [borderlessapps.com](https://borderlessapps.com) — hosts marketing, privacy policy, and support pages for all Borderless Apps.

## Structure

```
/                          → Main landing page
/WireWise/Marketing        → WireWise marketing page
/WireWise/PrivacyPolicy    → WireWise privacy policy
/WireWise/Support          → WireWise support page
/RepairScan/Marketing      → RepairScan marketing page
/RepairScan/PrivacyPolicy  → RepairScan privacy policy
/RepairScan/Support        → RepairScan support page
```

## Adding a New App

1. Create a new folder: `/AppName/`
2. Add subfolders: `Marketing/`, `PrivacyPolicy/`, `Support/` — each with an `index.html`
3. Add a new app card to `index.html`
4. Push to `main` — Cloudflare Pages auto-deploys

## Hosting

Deployed via Cloudflare Pages connected to this repo. Domain managed on Porkbun with Cloudflare nameservers.
