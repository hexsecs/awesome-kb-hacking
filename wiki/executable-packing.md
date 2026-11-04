---
uid: 01a1a876-3af3-7d8a-a927-65a165bb3772
title: "Executable Packing"
summary: "Resources about executable packing and unpacking"
type: entity
category: "Other Useful Repositories"
url: "https://github.com/packing-box/awesome-executable-packing"
status: unknown
created: 2026-11-04
updated: 2026-11-04
depth: brief
related: [malware-analysis, reverse-engineering, yara, reversing]
source_list: Awesome-Hacking
source_commit: 440486fd08b0a0d9ad9a041a0bb234dcdf65dee2
list_summary: "Resources about executable packing and unpacking"
sources:
  - url: "https://github.com/Hack-with-Github/Awesome-Hacking/blob/440486fd08b0a0d9ad9a041a0bb234dcdf65dee2/README.md"
    retrieved: 2026-11-04
  - url: "https://github.com/packing-box/awesome-executable-packing"
    retrieved: 2026-11-04
---

Resources about executable packing and unpacking

## What it is
The README calls this a curated list of resources on packing of executable formats, including PE and ELF, plus detection. Its listed content is literature (documentation and scientific research) together with packers and tools for detecting packers and unpacking binaries. It explains packing as altering an executable without changing its purpose, for example by bundling or compressing.

## Who it is for
Malware analysts and reverse engineers who need background on packers or tools to detect and unpack them.

## Caveats
- The README's own share link names a different owner (dhondta/awesome-executable-packing) than the repo recorded in the clone (packing-box); a rename or transfer is possible but was not confirmed.
- Packers and unpackers are dual-use; run unknown samples only in an isolated analysis environment.
- The README is large (about 120 KB), and only its first 20 KB was reviewed, so later entries are not described.

## Status and sources
Status is `unknown` until archive state is checked: a 2026-11-04 shallow clone of [packing-box/awesome-executable-packing](https://github.com/packing-box/awesome-executable-packing) shows the default branch last committed 2026-10-10, but GitHub's archived flag could not be read from this session.

## Related
- [Malware Analysis](malware-analysis.md) — Unpacking is one step in sample analysis
- [Reverse Engineering](reverse-engineering.md) — Core skills for working with packed binaries.
- [YARA](yara.md) — Rule-based detection tooling for binary samples
- [Reversing](reversing.md) — Collection of resources to learn Reverse Engineering from start
