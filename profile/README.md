<p align="center">
  <strong>Pragmatic infrastructure, routing, and network tooling.</strong>
</p>

<p align="center">
  <a href="https://makriq.casa">makriq.casa</a>
</p>

<p align="center">
  <a href="https://github.com/makriq-org/sys-cfg">sys-cfg</a>
  ·
  <a href="https://github.com/makriq-org/short-key-list">short-key-list</a>
  ·
  <a href="https://github.com/makriq-org/FlClash">FlClash</a>
  ·
  <a href="https://github.com/makriq-org/gov-and-it-pkg-names">gov-and-it-pkg-names</a>
</p>

---

## What we build

`makriq-org` maintains compact, production-oriented tooling around:

- network client configuration and distribution
- public routing artifacts and redirect-backed delivery
- Android package lists for split-tunneling and bypass flows
- opinionated infrastructure with explicit operational docs

The emphasis is simple: small moving parts, reproducible behavior, and artifacts that are easy to inspect.

## Public repositories

| Repository | Focus |
| --- | --- |
| [`sys-cfg`](https://github.com/makriq-org/sys-cfg) | Public service files, maintained routing rules, helper lists, and the redirect layer that exposes stable URLs. |
| [`short-key-list`](https://github.com/makriq-org/short-key-list) | Curated and checked VLESS key list with deduplication and historical scoring. |
| [`FlClash`](https://github.com/makriq-org/FlClash) | Independent `FlClash` fork with attention to Android usability, privacy, and cleaner releases. |
| [`gov-and-it-pkg-names`](https://github.com/makriq-org/gov-and-it-pkg-names) | Public package masks for Russian government and major Russian IT Android apps. |

## Working style

- concise repositories instead of monoliths
- public artifacts separated from private runtime state
- documentation that explains operational intent, not just file names
- stable URLs and predictable update paths for client-side integrations

## Notes

Some operational components stay private by design. The public side of the organization is intended to expose reusable artifacts, forks, and infrastructure-adjacent tooling without turning the org into a dump of internal state.
