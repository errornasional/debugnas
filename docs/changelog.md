---
layout: default
title: Changelog
---

## Agent Panel v0.5.22

Released on 2026-10-08

### New Features

- feat(billing): enforce per-plan tunnel quota + add TTL backstops for terminals/tunnels

### Bug Fixes

- fix(agent): use net.JoinHostPort for TCP tunnel dial (IPv6-safe)

### All Changes

<details><summary>View all</summary>

- fix(agent): use net.JoinHostPort for TCP tunnel dial (IPv6-safe) (a750a52)
- chore(agent): bump to Go 1.25 + deps — 0 reachable vulns (1f95e0b)
- feat(billing): enforce per-plan tunnel quota + add TTL backstops for terminals/tunnels (36d84b5)

</details>

## Quick Install

```bash
curl -sSL https://github.com/errornasional/debugnas/releases/latest/download/install.sh | sudo bash
```
