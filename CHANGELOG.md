# Changelog

All notable changes to this list will be documented in this file. Format follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/); versioning follows [Semantic Versioning](https://semver.org/) — MAJOR for category restructures, MINOR for connector additions, PATCH for description/URL fixes.

## [Unreleased]

### Planned for v1.4.0
- Continue folding in Enterprise-tier connectors visible only behind the Enterprise paywall: BioRender, ClickUp, Sentry, Mailchimp, Docusign, Open Targets, ICD-10 Codes, ActiveCampaign, Cloudinary, Bitly, Fireflies, Circleback, Honeycomb, MotherDuck, WordPress.com, Jotform, Microsoft OneNote, Google Workspace Admin, GoDaddy, Crypto.com, Blockscout, Trivago, Netlify, and others.
- Investigate publishing a separate `enterprise-only.md` for connectors that appear only behind the Enterprise paywall.
- Track Perplexity's documented surface vs the 400+ headline number — submit PRs to the Perplexity team for any Help-Center-documented connectors not yet visible in this list.

---

## [1.3.0] — 2026-05-15

### Added
- **Design and Creative** category (new, 13th overall) — for visual-design connectors.
- **Sales and Marketing** category (new, 14th overall) — separating outbound and lifecycle marketing from pure CRM.
- **Canva** under *Design and Creative* — in-thread design generation, history search, brand-compliant workflows.
- **Hugging Face** under *Research and Data* — model/dataset/Spaces discovery on the Hub.
- **Apollo.io** under *Sales and Marketing* — B2B contact + company data for prospect research.
- **Klaviyo** under *Sales and Marketing* — e-commerce marketing analytics + campaign queries.
- **Unwrap** under *Customer Support and CRM* — aggregated voice-of-customer feedback insights.

### Changed
- **Databricks** and **Snowflake** flagged with 💎 and labeled *Computer for Enterprise only* — they shipped May 4, 2026 as native AI data agents in Computer for Enterprise, not visible in the Pro-tier Computer Connectors UI. Earlier v1.2.0 listing omitted the tier flag.
- Sourced this update by diffing the live Computer Connectors UI (Pro tier) against the README, producing additions, removals, and tier corrections at the same time.
- Header: Connectors 41 → 44. Categories 12 → 14. Version 1.2.0 → 1.3.0.

### Removed
- **Linear** — no longer visible in the Pro-tier Computer Connectors UI as of May 15, 2026. Removed to keep the list grounded in what's actually addressable.
- **Shopify** — same: not visible in the current Pro-tier UI.

---

## [1.2.0] — 2026-05-15

### Added
- **Data and Analytics** category (12th overall) covering native AI-data-agent connectors.
- **Databricks** and **Snowflake** under the new category — both shipped as native data agents in Perplexity Computer on [May 4, 2026](https://www.perplexity.ai/changelog/improved-computer-models-and-enterprise-updates---may-4-2026). Live warehouse querying, semantic-layer-aware results, admin-managed permissions.
- About section reframed to acknowledge Perplexity's [400+ connector claim](https://www.aichatdaily.com/ai-tools/perplexity-personal-computer-mac-launch) across the Computer / Personal Computer surface — list scope clarified as a *curated Help-Center-documented subset*.
- About section: **Personal Computer GA on Mac** (May 7, 2026) and **1Password Unified Access partnership** (April 30, 2026) noted as infrastructure context.

### Changed
- Header: May 10 → May 15. Connectors 39 → 41. Categories 11 → 12. Version 1.1.0 → 1.2.0.
- Repositioned the list scope from "what's visible in Computer" to "curated Help-Center-documented subset of 400+ available," since the underlying surface is now an order of magnitude larger than what Perplexity publicly enumerates.

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

[Unreleased]: https://github.com/rdmgator12/Perplexity-Connectors-awesome-list-/compare/v1.3.0...HEAD
[1.3.0]: https://github.com/rdmgator12/Perplexity-Connectors-awesome-list-/compare/v1.2.0...v1.3.0
[1.2.0]: https://github.com/rdmgator12/Perplexity-Connectors-awesome-list-/compare/v1.1.0...v1.2.0
[1.1.0]: https://github.com/rdmgator12/Perplexity-Connectors-awesome-list-/compare/v1.0.0...v1.1.0
[1.0.0]: https://github.com/rdmgator12/Perplexity-Connectors-awesome-list-/releases/tag/v1.0.0
