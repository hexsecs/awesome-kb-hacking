# Activity log

## [2026-11-04] ingest | Awesome Hacking initial stub import

Imported all 81 curated resource rows from Hack-with-Github/Awesome-Hacking
at commit 440486fd08b0a0d9ad9a041a0bb234dcdf65dee2: 47 Awesome Repositories and
34 Other Useful Repositories. Preserved descriptions, categories, URLs,
source snapshot and CC0-1.0 license. All entries are stubs with unknown
resource status; outbound resource verification and recursive ingestion
are deferred.

## [2026-11-04] update | Restore traditional README list browsing

Generate a categorized resource list inline in README from the OpenShelf index,
with KB and upstream links for each entry. Preserve manual introduction and
license notices. Split oversized catalogs at category boundaries into linked
continuation pages below GitHub's display limit. Ingest maintains the view and
validation checks coverage, links, size and synchronization.

## [2026-11-04] deepen | Awesome-Hacking stubs → brief
Promoted all 81 entity stubs to `depth: brief`. Evidence: each upstream README and default-branch commit date captured by a 2026-11-04 shallow clone (CyberChef and GTFOBins via their GitHub source repos). GitHub repo pages could not be read, so archive state is unverified: every page stays `status: unknown` with no `last_checked`, and each body records the last-commit date instead. Drafted by four Sonnet lanes, checked line-by-line against the captured READMEs by two Haiku reviewers; 121 `related` links reciprocated. tools/check.py preservation test made depth-agnostic so it still runs once pages are no longer stubs.
