---
uid: 01a1a876-3af2-7313-97de-f6d267424fe9
title: "API Security Checklist"
summary: "Checklist of the most important security countermeasures when designing, testing, and releasing your API"
type: entity
category: "Other Useful Repositories"
url: "https://github.com/shieldfy/API-Security-Checklist"
status: unknown
created: 2026-11-04
updated: 2026-11-04
depth: brief
source_list: Awesome-Hacking
source_commit: 440486fd08b0a0d9ad9a041a0bb234dcdf65dee2
list_summary: "Checklist of the most important security countermeasures when designing, testing, and releasing your API"
related: [appsec, devsecops, web-security, security-cheatsheets]
sources:
  - url: "https://github.com/Hack-with-Github/Awesome-Hacking/blob/440486fd08b0a0d9ad9a041a0bb234dcdf65dee2/README.md"
    retrieved: 2026-11-04
  - url: "https://github.com/shieldfy/API-Security-Checklist"
    retrieved: 2026-11-04
---

Checklist of the most important security countermeasures when designing, testing, and releasing your API

## What it is
A single-page checklist of API hardening measures, written as tick-box items. The README groups them under Authentication, Access, Authorization (OAuth), Input, Processing, Output, CI and CD, and Monitoring, then adds a later "Advanced" part covering rate limiting, GraphQL, secrets management and zero trust. It also links a short see-also list and offers translated READMEs in many languages.

## Who it is for
Developers and reviewers who want a quick pre-release sanity check of an API design, and testers who want a list of controls to probe.

## Caveats
- Advice is terse and generic; it names controls but gives no implementation detail, so treat it as a prompt for review rather than a standard.
- Some items are opinionated (the README itself argues against JWT in favour of random API keys), so weigh them against your own threat model.
- The README links translated versions in many languages; this summary is based on the English text.

## Status and sources
Status is `unknown` until archive state is checked: a 2026-11-04 shallow clone of [shieldfy/API-Security-Checklist](https://github.com/shieldfy/API-Security-Checklist) shows the default branch last committed 2026-07-21, but GitHub's archived flag could not be read from this session.

## Related
- [AppSec](appsec.md) — complementary application security learning resources.
- [DevSecOps](devsecops.md) — tooling for the CI/CD and monitoring items this checklist raises.
- [Web Security](web-security.md) — deeper reading on the injection, XXE and OAuth issues it mentions.
- [Security Cheatsheets](security-cheatsheets.md) — OWASP Cheat Sheet Series for application security
