# CMA: configuration and ownership notice

This public repository contains legacy Cisco integration source. A separate `MeiRR17/Census` repository and `DevTeam1770/infrastructure/Census` also exist; these are **not assumed equivalent**. Do not merge, deploy or delete one based only on the repository name.

The tracked `Census/.env` file was removed from the latest branch. Use `Census/.env.example` only as a *non-operational* template. Environment-specific configuration belongs in a secret manager or local, ignored files. Because the historical repository was public, any **confirmed active** credentials formerly committed must be rotated; deleting a file from HEAD does not delete published commits.

This repository currently references `MeiRR17/axlerate-sdk` through `.gitmodules`. Once both repositories have been transferred to `DevTeam1770` and ownership/permission checked, update the submodule URL, pin and test the target commit. Until then, do not break the existing URL.

See the connected-side organizational migration procedure: [DevTeam1770/infrastructure/docs/CISCO-PORTFOLIO-MIGRATION-2026-11-01.md](https://github.com/DevTeam1770/infrastructure/blob/main/docs/CISCO-PORTFOLIO-MIGRATION-2026-11-01.md).
