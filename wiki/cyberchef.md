---
uid: 01a1a876-3af2-7b28-9359-d8bd3c4e4789
title: "CyberChef"
summary: "A simple, intuitive web app for analysing and decoding data without having to deal with complex tools or programming languages."
type: entity
category: "Other Useful Repositories"
url: "https://gchq.github.io/CyberChef/"
status: unknown
created: 2026-11-04
updated: 2026-11-04
depth: brief
source_list: Awesome-Hacking
source_commit: 440486fd08b0a0d9ad9a041a0bb234dcdf65dee2
list_summary: "A simple, intuitive web app for analysing and decoding data without having to deal with complex tools or programming languages."
related: [cryptography, malware-analysis, forensics]
sources:
  - url: "https://github.com/Hack-with-Github/Awesome-Hacking/blob/440486fd08b0a0d9ad9a041a0bb234dcdf65dee2/README.md"
    retrieved: 2026-11-04
  - url: "https://gchq.github.io/CyberChef/"
    retrieved: 2026-11-04
  - url: "https://github.com/gchq/CyberChef"
    retrieved: 2026-11-04
---

A simple, intuitive web app for analysing and decoding data without having to deal with complex tools or programming languages.

## What it is
A browser-based tool, which the README calls the "Cyber Swiss Army Knife", for chaining data operations: encodings such as Base64 and XOR, ciphers like AES, DES and Blowfish, hexdumps, compression, hashes and checksums, IPv6 and X.509 parsing, character-set conversion and more. You drag operations into a recipe, feed input and see output. The README also describes auto-baking, a Magic operation for detecting nested encodings, breakpoints, deep links to recipes, Docker and source builds, and Node.js and browser support.

## Who it is for
Analysts, CTF players and developers who need to decode or transform data without writing code.

## Caveats
- The README says all processing happens in the browser and nothing is sent to the web server, and that a local copy can be run (Docker or source); confirm the behaviour yourself before handling sensitive data.
- Magic detection is heuristic and can miss or mislabel encodings.
- The listed URL is the hosted app; the README describes the source repository.

## Status and sources
Status is `unknown` until archive state is checked: a 2026-11-04 shallow clone of the site's source repository [gchq/CyberChef](https://github.com/gchq/CyberChef) shows the default branch last committed 2026-11-04, but GitHub's archived flag could not be read from this session. The README states Apache 2.0.

## Related
- [Cryptography](cryptography.md) — background on the ciphers and hashes CyberChef applies.
- [Malware Analysis](malware-analysis.md) — decoding obfuscated payloads is a common use.
- [Forensics](forensics.md) — data carving and format conversion for investigations.
