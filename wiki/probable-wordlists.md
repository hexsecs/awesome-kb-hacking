---
uid: 01a1a876-3af4-7f71-ba7a-e47d16257eaf
title: "Probable Wordlists"
summary: "Wordlists sorted by probability originally created for password generation and testing"
type: entity
category: "Other Useful Repositories"
url: "https://github.com/berzerk0/Probable-Wordlists"
status: unknown
created: 2026-11-04
updated: 2026-11-04
depth: brief
related: [password-cracking, seclists, cryptography]
source_list: Awesome-Hacking
source_commit: 440486fd08b0a0d9ad9a041a0bb234dcdf65dee2
list_summary: "Wordlists sorted by probability originally created for password generation and testing"
sources:
  - url: "https://github.com/Hack-with-Github/Awesome-Hacking/blob/440486fd08b0a0d9ad9a041a0bb234dcdf65dee2/README.md"
    retrieved: 2026-11-04
  - url: "https://github.com/berzerk0/Probable-Wordlists"
    retrieved: 2026-11-04
---

Wordlists sorted by probability originally created for password generation and testing

## What it is
Password wordlists sorted by how often each password appears rather than alphabetically. The README says the author gathered leaked-password lists, kept only passwords seen at least five times, and ended with about 2 billion passwords sorted by popularity. The repository holds links rather than the data itself, with a downloads page; folders cover real passwords, dictionary-style lists and analysis files such as Hashcat rules and masks.

## Who it is for
Password auditors and researchers, and anyone who wants to see what common passwords look like.

## Caveats
- Last commit was in 2019, so newer leaks and trends are missing.
- The lists derive from real breach data; use them for authorized audits and defensive checks only.
- Downloads are hosted elsewhere, so check that the links still work.
- For tooling around cracking see [Password Cracking](password-cracking.md).

## Status and sources
Status is `unknown` until archive state is checked: a 2026-11-04 shallow clone of [berzerk0/Probable-Wordlists](https://github.com/berzerk0/Probable-Wordlists) shows the default branch last committed 2019-12-04, but GitHub's archived flag could not be read from this session.

## Related
- [Password Cracking](password-cracking.md) — Tools that consume these lists
- [SecLists](seclists.md) — Broader wordlist and payload collection
- [Cryptography](cryptography.md) — Hashing and encryption background
