## What’s new in 1.37.0

## What's Changed
- Check upstream https://github.com/dani-garcia/vaultwarden/releases/tag/1.37.0

### Security Fixes
This release contains security fixes for the following advisories. We strongly advice to update as soon as possible.

- SSRF via the icon endpoint [GHSA-hw4g-2v3f-74x5] [GHSA-vh5m-fc9v-m84g] (Medium, 5.8 / 6.3)
- Cross-Organization Cipher Access [GHSA-xwf8-pjh7-h589] (Medium, 5.9)
- Organization Policy Bypass on Directory Import [GHSA-88qc-6ch9-mc3j] (Medium, 5.5)
- Send Access-Count Bypass [GHSA-rxhg-2pw9-vf25] (Medium, 5.3)
- Unauthenticated WebSocket Flooding DDOS [GHSA-96f7-78q5-j345] (Medium, 5.3)
- Cross-Organization Secret Sharing [GHSA-455c-vgg9-jxw8] (Medium, 4.3)
- Organization Import Authorization [GHSA-f3qw-qg77-hmm4][GHSA-jq2g-h4xr-4mcr] (Medium, 4.3)
- Organization Data Enumeration via the Manager role [GHSA-rqf8-2568-r7mc] (Medium, 4.3)
- These are private for now, pending CVE assignment and publishing at a later date.

### What's Changed
- OpenDAL S3 parameter support by @txase in #6127
- Fix SSO Cookie path by @BlackDex in #7187
- fix email 2fa for bw cli by @stefan0xC in #7225
- sso_auth improvements by @Timshel in #7197
- Reject unrecognised DATABASE_URL instead of silent SQLite fallback by @mfw78 in #7061
- Switch to xx-cargo by @dfunkt in #6640
- Updates and fixes by @BlackDex in #7235
- Switch to Edition 2024, more clippy lints, and less macro calls by @BlackDex in #7200
- Serve Apple app site association file by @user71424q in #7191
- Update Rust, Crates and GHA by @BlackDex in #7307
- Fix enforce blocked by @Timshel in #7246
- Admin password recovery endpoint change by @Timshel in #7270
- fix(sends): emit hideEmail as non-null boolean in sync response by @kvdb in #7283
- Org membership delete remove Invitation by @Timshel in #7284
- [v2026.5.0] Registration request update by @Timshel in #7295
- [v2026.5.0] PutPolicy now using vnext format by @Timshel in #7296
- 2026.6.0 send support by @Timshel in #7346
- Add SSO_AUTHORIZE_BODY by @Timshel in #7357
- Add pm-26340-linux-biometrics-v2 feature flag by @pilotstew in #7358
- improve CI by @TriplEight in #6991
- Misc updates and fixes by @BlackDex in #7406
- Remove old compatibility code by @Timshel in #7434
- Fix compilation with newer rust-musl version by @dfunkt in #7453
- Fix Custom Role CSS for new dialog markup by @tom27052006 in #7442
- Remove unused fields by @Timshel in #7458
- Update API response, crates and GHA by @BlackDex in #7470
- Trusted proxy support, unauthenticated rate limit & other fixes by @dani-garcia in #7472
