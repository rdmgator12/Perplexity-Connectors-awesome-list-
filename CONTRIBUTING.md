# Contributing

This list tracks the connectors visible in Perplexity's Computer integration surface, with v1.1 expansion planned to cover Enterprise-tier connectors as well. Contributions welcome.

> This is an independent, community-maintained project. Not affiliated with, endorsed by, or sponsored by Perplexity AI, Inc.

## What You Can Contribute

### New Connectors
When Perplexity adds new connectors to the directory (Computer, Pro, or Enterprise tiers), submit a PR adding them to the appropriate category with a description and use case. Please note the tier the connector is visible at in the PR description.

### Improved Descriptions
If a description or use case is missing detail or could be more helpful, submit a PR with a better one.

### Category Corrections
If a connector is in the wrong category, submit a PR moving it.

### Field Reports
Tested a connector and have real-world notes? Add a brief field report below the connector entry:

```markdown
- [Connector Name](https://example.com) - Description. *Use case: ...*
  > **Field report:** One paragraph on what worked, what didn't, what surprised you. Be specific.
```

## Guidelines

- One PR per change unless closely related.
- Keep descriptions concise — one sentence for the description, one for the use case.
- Use cases should be specific and practical, not marketing copy.
- Don't add connectors that aren't in Perplexity's official directory. This list tracks Perplexity's curated connector surface, not all MCP servers (see [awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) for that).
- Link to the connector vendor's canonical homepage, not to a Perplexity help-center article (exception: Perplexity-internal connectors with no external vendor surface, like Medical Records and Health and Fitness Apps).
- Maintain alphabetical order within categories.

## Tier Tracking

Perplexity exposes connectors across multiple tiers:

- **Computer** — visible to users with access to the Computer integration surface.
- **Pro** — File App Connectors for Pro subscribers (Google Drive, Notion, Asana, Jira, Confluence, etc. — overlap with Computer).
- **Enterprise** — broader directory including BioRender, ClickUp, Snowflake, Sentry, Klaviyo, Mailchimp, Docusign, Open Targets, ICD-10 Codes, and more.

If you contribute a connector that is only visible at a specific tier, mention that in the PR.

## Updates

This list is updated as Perplexity's directory changes. If you notice connectors that have been added or removed and aren't reflected here, please open an issue or PR.
