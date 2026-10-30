# VILLARA-only release manifest — review, not deployment

Repository: eternalimit/trusted-links
Branch: review/villara-seo-20261030
Date: 2026-10-30
Scope: Only the two existing original HTML campaign files listed below. No other files approved for public packaging.

| Path | Bytes | Git blob SHA-1 | SHA-256 |
| --- | ---: | --- | --- |
| index.html | 1678 | 40b9814ef7ea72ce9e0a099f7b87a08df0b0d94d | d142a3f1a37b43c962b87568241a27f35b8f77d6414e6493cb707be18f62f1cf |
| campaigns/villara/index.html | 2220 | 198e63825c30fb409ccbcc25c869c2cf3fb8d2a0 | 17b578d017a34c6e7f4a44ee9821fa66e2fd328d5324846e9d67a43f0ad058bb |

Hashes were computed over exact UTF-8 bytes matching the fetched Git blob IDs; these are source-file hashes, not live deployment hashes.

Verification: homepage links to ./campaigns/villara/index.html; both pages link to https://villara.com/ and retain noindex,follow. No third-party marketing images or private contract content included in these two HTML files.

Exclusions: all other repository files and folders, including ARCHIVE, audit, handoffs, bundles, and any MASTER.ORIGIN Edition 0 HOLD materials. CATBOT 100 is strictly out of scope: do not access, copy, modify, test, or deploy it.

RELEASE GATE: HOLD. No merge, no deployment, no indexing submission. Confirm public hosting destination, build a deploy artifact consisting solely of approved files, verify exact deployed bytes, and approve before publishing.
