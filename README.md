# Typai ↔ Base44 Link Setup

This repository now includes a Base44 app manifest so the project can be opened as the **Typai** app from the Base44 platform.

## What's included

- `base44.manifest.json`: declares the Base44 app identity (`typai`) and open/deep-link URLs.

## Finalize in Base44

1. Create (or open) the app in Base44 with slug **`typai`**.
2. In Base44 app settings, connect this repository.
3. Replace `"<org-or-user>/Typai"` in `base44.manifest.json` with the real GitHub path.
4. Confirm the app launch URL is:
   - `https://base44.app/apps/typai/open`
5. Confirm deep-link handling for:
   - `base44://apps/typai/open`

Once those are set, opening Typai from Base44 should route into this app configuration.
