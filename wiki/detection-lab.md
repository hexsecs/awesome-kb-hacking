---
uid: 01a1a876-3af2-7ba8-998b-9da26b84c77c
title: "Detection Lab"
summary: "Vagrant & Packer scripts to build a lab environment complete with security tooling and logging best practices"
type: entity
category: "Other Useful Repositories"
url: "https://github.com/clong/DetectionLab"
status: unknown
created: 2026-11-04
updated: 2026-11-04
depth: brief
source_list: Awesome-Hacking
source_commit: 440486fd08b0a0d9ad9a041a0bb234dcdf65dee2
list_summary: "Vagrant & Packer scripts to build a lab environment complete with security tooling and logging best practices"
related: [detection-engineering, capsulecorp-pentest, threathunter-playbook, honeypots]
sources:
  - url: "https://github.com/Hack-with-Github/Awesome-Hacking/blob/440486fd08b0a0d9ad9a041a0bb234dcdf65dee2/README.md"
    retrieved: 2026-11-04
  - url: "https://github.com/clong/DetectionLab"
    retrieved: 2026-11-04
---

Vagrant & Packer scripts to build a lab environment complete with security tooling and logging best practices

## What it is
The README describes Vagrant and Packer scripts that build a Windows domain lab preloaded with security tooling and logging configuration, designed with defenders in mind. Its first heading states that, as of 2023-01-01, DetectionLab is no longer actively maintained.

## Who it is for
Defenders who want a lab to generate and examine logs, accepting that the project is unmaintained.

## Caveats
- The README says the lab is not hardened and uses default Vagrant credentials; do not connect or bridge it to networks you care about.
- Per the README it is no longer maintained, so builds may break against current boxes and tool versions.
- For an attacker-oriented lab see [Capsulecorp Pentest](capsulecorp-pentest.md).

## Status and sources
Status is `unknown` until archive state is checked: a 2026-11-04 shallow clone of [clong/DetectionLab](https://github.com/clong/DetectionLab) shows the default branch last committed 2023-03-26, but GitHub's archived flag could not be read from this session.

## Related
- [Detection Engineering](detection-engineering.md) — Detection engineering concepts and frameworks
- [Capsulecorp Pentest](capsulecorp-pentest.md) — Attacker-oriented lab, the offensive counterpart
- [ThreatHunter-Playbook](threathunter-playbook.md) — Threat-hunting techniques for defender lab data
- [Honeypots](honeypots.md) — List of honeypot resources
