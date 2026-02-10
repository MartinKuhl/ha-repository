## What’s changed 1.35.3
- update to newest Vaultwarden version

## Security Fixes
- [GHSA-h265-g7rm-h337](https://github.com/dani-garcia/vaultwarden/security/advisories/GHSA-h265-g7rm-h337)
This vulnerability would allow an authenticated attacker that is part of an organization to access items from collections to which the attacker does not belong.

## What's Changed ([Upstream](https://github.com/dani-garcia/vaultwarden/releases/tag/1.35.3))
- Fix User API Key login by @BlackDex
- use email instead of empty name for webauhn by @stefan0xC
- hide password hints via CSS by @stefan0xC
- fix email as 2fa with auth requests by @stefan0xC
- Update crates, web-vault, js, workflows by @BlackDex
- refactor: improve tooltips in diagnostics page by @tessus
- Empty AccountKeys when no private key by @Timshel
- fix error message for purging auth requests by @stefan0xC
- Misc updates, crates, rust, js, gha, vault by @BlackDex
- Update crates and web-vault by @BlackDex
- Fix org-details issue by @BlackDex
