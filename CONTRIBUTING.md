# Contributing

Thanks for your interest. These projects target embedded VoIP on RTOS / cellular
handheld radios — a narrow niche, so contributions should keep that scope.

## Ground rules

- **Keep the core portable.** `core/` depends only on mbedTLS and ed25519. Anything
  platform-specific belongs in a port (`ports/<target>/`) or device (`devices/<name>/`) folder.
- **No AI-slop.** Terse, factual commits, comments, and docs. Explain the non-obvious; skip the obvious.
- **One logical change per PR.**

## Build & test

- **ts3-core:** `sh build.sh && ./out/selftest && ./out/port_conformance` (see its README).
- **ts3-quecpython:** run a device module's `demo()` on the target.

## Commits & PRs

- Conventional-ish messages: `feat:`, `fix:`, `docs:`, `refactor:`, `chore:`.
- Say what changed and why; link the issue.

## Reporting

- **Bugs:** open an issue with the template.
- **Security:** see [SECURITY.md](SECURITY.md) — do not open a public issue for vulnerabilities.
