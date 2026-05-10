# Changelog

All notable changes to this list will be documented in this file. Format follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/); versioning follows [Semantic Versioning](https://semver.org/) — MAJOR for category restructures, MINOR for connector additions, PATCH for description/URL fixes.

## [Unreleased]

### Planned for v1.1.0
- Fold in Enterprise-tier connectors visible only on Perplexity's Enterprise directory: BioRender, ClickUp, Snowflake, Sentry, Klaviyo, Mailchimp, Docusign, Open Targets, ICD-10 Codes, ActiveCampaign, Cloudinary, Bitly, Fireflies, Circleback, Honeycomb, MotherDuck, WordPress.com, Jotform, Microsoft OneNote, Google Workspace Admin, GoDaddy, Crypto.com, Blockscout, Trivago, Databricks, Netlify, and others.
- Add `awesome-lint` to CI once the repo is ≥30 days old (lint blocks submissions on `git-repo-age` until 2026-06-09).

---

## [1.1.0] — 2026-05-10

### Added
- **About** section under the header with single-paragraph context.
- **CHANGELOG.md** (this file) tracking version history.
- **code-of-conduct.md** adopting Contributor Covenant 2.1.
- **Legend** block with `💎` (Premium-tier) and `🎖️` (Perplexity-internal) emoji prefixes applied to relevant entries.
- Badges row under H1: License (CC0-1.0), Last Commit, Track Awesome List.
- **Related** section expanded with reciprocal links to the sister `awesome-claude-connectors` list.

### Changed
- LICENSE relicensed from MIT to **CC0-1.0** to match the awesome-list canonical convention.
- TOC anchor naming standardized; per-entry descriptions audited for `awesome-lint` per-item compliance (`[Name](url) - Description.` shape, period-terminated, no name-restating short descriptions where avoidable).
- Tightened category boundaries; minor wording improvements to use cases.

---

## [1.0.0] — 2026-05-10

### Added
- Initial seed: **39 connectors across 11 categories** mirroring the [Perplexity Computer connectors surface](https://www.perplexity.ai/computer/connectors).
- README.md modeled on `awesome-claude-connectors` structure.
- CONTRIBUTING.md with tier-tracking guidelines (Computer / Pro / Enterprise).
- LICENSE (MIT at v1.0.0; relicensed CC0-1.0 in v1.1.0).
- All 39 connector URLs verified via Exa web search — caught Carbon Arc on `.ai` (not `.com`), Lucid on `.co` (not `.com`), Jam on `.dev` (not `.com`).

### Categories
Communication and Email · Customer Support and CRM · Development Tools · Documents and Files · Finance and Investing · Healthcare and Life Sciences · Legal · Lifestyle and Local · Productivity and Notes · Project Management · Research and Data.

[Unreleased]: https://github.com/rdmgator12/Perplexity-Connectors-awesome-list-/compare/v1.1.0...HEAD
[1.1.0]: https://github.com/rdmgator12/Perplexity-Connectors-awesome-list-/compare/v1.0.0...v1.1.0
[1.0.0]: https://github.com/rdmgator12/Perplexity-Connectors-awesome-list-/releases/tag/v1.0.0
