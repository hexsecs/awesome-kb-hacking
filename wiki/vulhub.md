---
uid: 01a1a876-3af4-7936-aff7-5d5e2f5fdab7
title: "Vulhub"
summary: "Pre-Built Vulnerable Environments Based on Docker-Compose"
type: entity
category: "Other Useful Repositories"
url: "https://github.com/vulhub/vulhub"
status: unknown
created: 2026-11-04
updated: 2026-11-04
depth: brief
related: [cyber-skills, cve-poc, capsulecorp-pentest]
source_list: Awesome-Hacking
source_commit: 440486fd08b0a0d9ad9a041a0bb234dcdf65dee2
list_summary: "Pre-Built Vulnerable Environments Based on Docker-Compose"
sources:
  - url: "https://github.com/Hack-with-Github/Awesome-Hacking/blob/440486fd08b0a0d9ad9a041a0bb234dcdf65dee2/README.md"
    retrieved: 2026-11-04
  - url: "https://github.com/vulhub/vulhub"
    retrieved: 2026-11-04
---

Pre-Built Vulnerable Environments Based on Docker-Compose

## What it is
Per the README, an open-source collection of pre-built vulnerable Docker environments that launch with one command for security research, learning or demonstration. It has a Quick Start, troubleshooting, contribution and partner sections, and a companion site at vulhub.org.

## Who it is for
Learners and researchers who need a disposable, reproducible vulnerable target for known issues.

## Caveats
- Environments are deliberately vulnerable; run them in an isolated network.
- Requires Docker; the README includes install and troubleshooting steps.
- For exploit references see [CVE PoC](cve-poc.md).
- Only the README was reviewed, not individual environments.

## Status and sources
Status is `unknown` until archive state is checked: a 2026-11-04 shallow clone of [vulhub/vulhub](https://github.com/vulhub/vulhub) shows the default branch last committed 2026-10-18, but GitHub's archived flag could not be read from this session.

## Related
- [Cyber Skills](cyber-skills.md) — Hacking environments for legal skill training
- [CVE PoC](cve-poc.md) — CVE proof-of-concept exploit collection
- [Capsulecorp Pentest](capsulecorp-pentest.md) — Vagrant and Ansible pentest lab
