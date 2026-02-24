## What’s new in 1.35.4B

## Security Fixes

This release contains security fixes for the following advisories. We strongly advice to update as soon as possible.

- GHSA-w9f8-m526-h7fh. This vulnerability would allow an attacker to access a cipher from a different user (fully encrypted) if they already know its internal UUID.
- GHSA-h4hq-rgvh-wh27. This vulnerability allows an attacker with manager-level access within an organization to modify collections they can access, even if they do not have management permissions for them.
- GHSA-r32r-j5jq-3w4m. This vulnerability allows an attacker with manager-level access within an organization to modify collections they are not assigned.
- These are private for now, pending CVE assignment.

## What's Changed

- Update Rust and Crates and GHA
- hide remember 2fa token
- fix(send_invite): invite link
- organization