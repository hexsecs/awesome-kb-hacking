---
uid: 01a1a876-3af3-7809-a1b8-f7bd7dd915a4
title: "Payloads"
summary: "Collection of web attack payloads"
type: entity
category: "Other Useful Repositories"
url: "https://github.com/foospidy/payloads"
status: unknown
created: 2026-11-04
updated: 2026-11-04
depth: brief
related: [payloadsallthethings, seclists, web-hacking, cve-poc, gtfobins]
source_list: Awesome-Hacking
source_commit: 440486fd08b0a0d9ad9a041a0bb234dcdf65dee2
list_summary: "Collection of web attack payloads"
sources:
  - url: "https://github.com/Hack-with-Github/Awesome-Hacking/blob/440486fd08b0a0d9ad9a041a0bb234dcdf65dee2/README.md"
    retrieved: 2026-11-04
  - url: "https://github.com/foospidy/payloads"
    retrieved: 2026-11-04
---

Collection of web attack payloads

## What it is
A repository of web attack payloads. The README describes a get.sh script that downloads external payload sets and unzips compressed ones, with credits for sources such as OWASP, other collections and CTF-derived requests. The README says the CTF material is mostly raw captured requests, so not every entry is a real payload.

## Who it is for
Testers and tool authors who want raw payload files to feed scanners or fuzzers.

## Caveats
- Last commit was in 2021, so the data is dated and may miss newer techniques.
- Much of it is aggregated from other projects, as the credits show; expect noise and duplicates.
- Use payloads only against targets you are authorized to test.
- [PayloadsAllTheThings](payloadsallthethings.md) is listed in its credits and organises payloads into per-topic folders.

## Status and sources
Status is `unknown` until archive state is checked: a 2026-11-04 shallow clone of [foospidy/payloads](https://github.com/foospidy/payloads) shows the default branch last committed 2021-04-22, but GitHub's archived flag could not be read from this session.

## Related
- [PayloadsAllTheThings](payloadsallthethings.md) — Documented, topic-organised payload reference
- [SecLists](seclists.md) — Wordlists and fuzzing payloads
- [Web Hacking](web-hacking.md) — Broader web hacking resources
- [CVE PoC](cve-poc.md) — List of CVE Proof of Concepts (PoCs) updated daily by Trickest
- [GTFOBins](gtfobins.md) — A curated list of Unix binaries that can be exploited by an attacker to…
