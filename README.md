# Hacking (Awesome KB)

An [OpenShelf](https://github.com/OpenNorms/openshelf) 1.7 knowledge base,
ingested from [Hack-with-Github/Awesome-Hacking](https://github.com/Hack-with-Github/Awesome-Hacking).
Part of the [Awesome KB](https://github.com/hexsecs/awesome-kb) network.

**[Browse the knowledge base](index.md)** — 81 resources, all at `depth: stub`.

## Scope

This imports the source list's two curated tables: Awesome Repositories and
Other Useful Repositories. It does not recursively ingest the linked lists,
advertisements, badges, contribution links, or social links.

The list stays canon; ingestion flows list → KB. Stubs preserve each listed
description and resource URL. Resource maintenance status is `unknown`;
`last_checked` is absent until the resource itself is verified.

## Reproduce the import

```sh
python3 tools/ingest.py --date 2026-11-04
```

The default input is the immutable capture under `raw/2026-11-04/`.
For a newer upstream checkout, use `--source /path/to/Awesome-Hacking`.
Existing UUIDs, creation dates, authored bodies, depths, and verification
stamps survive re-ingestion. Generated indexes should not be hand-edited.

## Validation

```sh
python3 tools/check.py
openshelf lint .
```

CI runs both checks and confirms ingest produces no tracked changes.

## License and attribution

CC0-1.0, following the upstream list's [LICENSE](LICENSE).
Descriptions are imported from Awesome-Hacking; this does not apply CC0 to
the linked projects, which retain their own licenses.
Source revision: [440486fd08b0a0d9ad9a041a0bb234dcdf65dee2](https://github.com/Hack-with-Github/Awesome-Hacking/tree/440486fd08b0a0d9ad9a041a0bb234dcdf65dee2).

