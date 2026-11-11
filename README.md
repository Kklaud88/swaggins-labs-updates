# Swaggin's Labs Updates

Public release channel used by Swaggin's Portal Hub.

Portal Hub reads `updates.json`, downloads only HTTPS packages, and verifies the exact SHA-256 value before installation. Failed or interrupted installs are rolled back. This repository contains friend-safe portable application packages only; it does not contain personal settings, recordings, identities, tokens, or USB data.

Current channel: [initial release](https://github.com/Kklaud88/swaggins-labs-updates/releases/tag/initial-2026.11.11).

Future publishing rule: upload the new ZIP first, calculate and verify its SHA-256, then add a higher semantic version to `updates.json`. Existing entries remain available for restore and rollback.