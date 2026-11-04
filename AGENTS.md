# Maintainer schema — Hacking (Awesome KB)

This KB follows OpenShelf 1.7, profile awesome. The specification in
OpenNorms/openshelf is the format authority. See kb.yaml for layout.
The maintenance method lives in hexsecs/awesome-kb-skill.

## Canon and scope

Hack-with-Github/Awesome-Hacking is canon, designated by the owner's request
to import the Awesome Hacking list on 2026-11-04. Ingestion flows list → KB.
Only resources in the two curated tables receive entity pages. Do not
recursively ingest linked lists or add unlisted resources.

## Layout and ingest

- wiki/<slug>.md: one entity per table row.
- wiki/index-<category>.md: generated category indexes.
- index.md: generated L1 index; every entity is reachable.
- raw/<capture-date>/: immutable README and capture metadata.
- raw/MANIFEST.sha256: captured source checksums.
- tools/ingest.py: parses the two Markdown tables.
- log.md: append-only operations log.

Run python3 tools/ingest.py --date YYYY-MM-DD. Default source is the initial
capture; --source may name an upstream git checkout or a capture directory
with README.md and capture.json. A new source must be preserved as a new
capture; never overwrite old captures. Re-run until no files change.

## Fields

Summary is derived from the list description and capped at 160 characters;
list_summary and the first body paragraph preserve the complete description.
New pages receive a random UUIDv7, created/updated dates of ingestion,
depth: stub and status: unknown. Do not stamp last_checked until the listed
resource's URL and maintenance state have actually been verified. The source
citation is pinned to the captured upstream commit.

Preserve uid and created forever; preserve authored brief/full/deep bodies,
depth, status, last_checked and extra source records during ingest rewrites.
Generated indexes must not be hand-edited. Delisted entities are retained
with a tombstone note, never deleted.

## Gates

Run python3 tools/check.py, confirm a second ingest changes no content, and
run openshelf lint . before landing. CI runs these checks. Unverified stub
freshness warnings are expected; never suppress them with invented dates.

