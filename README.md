# Borderless Apps Site

Static site for [borderlessapps.com](https://borderlessapps.com) — the shared documentation home for Borderless Apps products. It hosts marketing, privacy policy, and support pages for each app.

## Structure

```
/                           -> Main landing page
/WireWise/Marketing         -> WireWise marketing page
/WireWise/PrivacyPolicy     -> WireWise privacy policy
/WireWise/Support           -> WireWise support page
/RepairScore/Marketing      -> RepairScore marketing page
/RepairScore/PrivacyPolicy  -> RepairScore privacy policy
/RepairScore/Support        -> RepairScore support page
/CitizenReady/Marketing     -> CitizenReady marketing page
/CitizenReady/PrivacyPolicy -> CitizenReady privacy policy
/CitizenReady/Support       -> CitizenReady support page
/PetChip/Marketing          -> PetChip marketing page
/PetChip/PrivacyPolicy      -> PetChip privacy policy
/PetChip/Support            -> PetChip support page
```

## Adding a New App

1. Create a new folder: `/AppName/`
2. Add subfolders: `Marketing/`, `PrivacyPolicy/`, `Support/` — each with an `index.html`
3. Add a new app card to `index.html`
4. Push to `main` — Cloudflare Pages auto-deploys

## Hosting

Deployed via Cloudflare Pages connected to this repo. Domain managed on Porkbun with Cloudflare nameservers.
