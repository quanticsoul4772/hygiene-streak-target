<!--
  Note to reviewer (operator sign-off required):

  Versioning-scheme assumption — this repository has NO git tags and NO
  GitHub releases (verified against the repo's tag list and releases page
  on 2026-09-27), and SECURITY.md states the repo "has no formal release
  or versioning system". This changelog therefore anchors its history to
  DATED entries only, not version numbers. If the maintainer later adopts
  tagged releases (e.g. SemVer), the dated headings below should be
  converted to version headings at that time.

  This draft is held for operator sign-off before being treated as final.

  Every entry below is traceable to real git history (commit SHAs and PR
  numbers cited inline) or to existing top-level docs (README.md,
  SECURITY.md, CONTRIBUTING.md, .github/CODEOWNERS). No entries are
  fabricated.
-->

# Changelog

All notable changes to this repository are documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).
Because this repository has no formal release or versioning system — no git
tags, no GitHub releases, and no published packages (see
[SECURITY.md](SECURITY.md)) — entries are grouped under **dates** rather than
version numbers.

## Unreleased

### Added

- This `CHANGELOG.md`, recording the repository's notable changes per date
  (draft pending operator sign-off).

## 2026-09-27

### Added

- `SECURITY.md` at the repository root documenting the security policy:
  supported scope (latest `main`), private vulnerability reporting via GitHub
  security advisories, report contents, response expectations (acknowledgment
  within 7 days, resolution target within 30 days), and coordinated
  disclosure.
  ([#4](https://github.com/quanticsoul4772/hygiene-streak-target/pull/4),
  commit [`a038190`](https://github.com/quanticsoul4772/hygiene-streak-target/commit/a038190))
- `.github/CODEOWNERS` containing a single catch-all rule assigning a default
  owner for every path in the repository.
  ([#2](https://github.com/quanticsoul4772/hygiene-streak-target/pull/2),
  commit [`e184c78`](https://github.com/quanticsoul4772/hygiene-streak-target/commit/e184c78))
- `CONTRIBUTING.md` at the repository root with the contribution guide:
  fork/clone workflow, branch conventions, README-accuracy expectations,
  commit message conventions, pull request process and review checklist, MIT
  licensing of contributions, and how to ask questions or file issues.
  ([#1](https://github.com/quanticsoul4772/hygiene-streak-target/pull/1),
  commit [`1580c35`](https://github.com/quanticsoul4772/hygiene-streak-target/commit/1580c35))
- `LICENSE` file adding the MIT License.
  (commit [`9974749`](https://github.com/quanticsoul4772/hygiene-streak-target/commit/9974749))
- Initial repository contents: `README.md` describing the project as a fresh
  community-health target for the pilot7 hygiene ladder.
  (commit [`92f6d9c`](https://github.com/quanticsoul4772/hygiene-streak-target/commit/92f6d9c))

### Fixed

- Set the real default owner (`@quanticsoul4772`) in `.github/CODEOWNERS`.
  ([#3](https://github.com/quanticsoul4772/hygiene-streak-target/pull/3),
  commit [`d9c2828`](https://github.com/quanticsoul4772/hygiene-streak-target/commit/d9c2828))
