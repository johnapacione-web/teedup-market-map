# TEEDUP — locked interactive map access

## Accepted v0.8 commercial planning derivative

- Live interactive map: https://johnapacione-web.github.io/teedup-market-map/COM-MAP-001_v0.8_LOCKED.html
- Existing accepted link retained: https://johnapacione-web.github.io/teedup-market-map/review-v08.html
- Exact accepted source: https://github.com/johnapacione-web/teedup-market-map/blob/6f9cc73b5aaae80cf01614948dcbb1ec0b0ed48c/review-v08.html
- SHA-256: `280b525e9636190f72c311587fd9f7015737c46b50d022d83b116d1a03bb0252`
- Git blob: `0029a306ac210669780395573f892ad9311cc2d2`
- Validation: [validation-v08.json](validation-v08.json)
- Formal lock register: [MAP_LOCKS.json](MAP_LOCKS.json)

The user confirmed that the live map looks good and is functional, then explicitly instructed that this map version and access be locked. The exact tested HTML is preserved, including its existing REVIEW/UNRELEASED wording; this acceptance record governs its formal locked status. No cosmetic content was silently changed after acceptance.

Open the live hyperlink in a browser. A screenshot shown in a chat is only a visual illustration and is not the interactive artifact. No GitHub login is required to use the public map. Bookmark the version-named live URL.

## Original v0.5

The formally locked Ontario/Florida master remains unchanged at https://johnapacione-web.github.io/teedup-market-map/ . Do not replace its index.html.

## Locked scope

1,938 existing Ontario/Florida records, legacy histories and comparator values are preserved. v0.8 includes 383 South Carolina source records for approved commercial planning. Formal South Carolina CAC-001/SOI-001 certification remains pending. The 384-row scenario accounting ledger and its supplemental proposed Mount Vintage nine remain disclosed separately from the 383 mapped source records.

## Continuing work and recovery

Future markets or corrections require new versioned files. Keep both accepted live links working. Compare locked file hashes before and after every deployment. The integrity workflow detects changes but is not a repository write-protection rule. The exact source can be recovered from its immutable Git commit/blob if a live path is accidentally changed.

The live map uses external Leaflet/MarkerCluster CDN assets and OpenStreetMap tiles. A preservation lock does not guarantee third-party service uptime; no proxy, substitute basemap or screenshot fallback may be silently presented as the accepted map.
