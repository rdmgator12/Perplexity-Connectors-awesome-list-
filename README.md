# Awesome Perplexity Connectors [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)
[![Last Commit](https://img.shields.io/github/last-commit/rdmgator12/Perplexity-Connectors-awesome-list-)](https://github.com/rdmgator12/Perplexity-Connectors-awesome-list-/commits/main)
[![Track Awesome List](https://www.trackawesomelist.com/badge.svg)](https://www.trackawesomelist.com/rdmgator12/Perplexity-Connectors-awesome-list-/)

> A curated directory of every connector available in Perplexity's [Computer](https://www.perplexity.ai/computer) integration surface — connect services so Computer can access and act on your data.

**Last updated:** May 15, 2026 · **Connectors curated:** 41 · **Perplexity claims:** 400+ available · **Categories:** 12 · **Version:** 1.2.0

Perplexity Connectors are integrations that let Perplexity's Computer feature read from and act on your accounts at third-party services — email, files, project trackers, CRMs, financial data, healthcare records, and more. They power retrieval-augmented answers grounded in your own data and, where supported, agentic actions (creating tasks, updating CRM records, posting messages).

This list tracks the connectors documented in the Perplexity Computer Help Center as of the **Last updated** date. As of [May 7, 2026](https://www.aichatdaily.com/ai-tools/perplexity-personal-computer-mac-launch) Perplexity describes the broader Computer + Personal Computer surface as carrying **400+ connectors** — most of which are not individually documented on a public page. This list is therefore a *curated subset* of that universe, focused on connectors with first-party Help Center coverage. Perplexity also exposes additional connectors at the Pro and Enterprise tiers.

**Personal Computer** (Mac, [GA May 7, 2026](https://tech.yahoo.com/ai/perplexity-ai/articles/perplexity-personal-computer-now-available-195759629.html)) extends the cloud Computer agent onto local files, native macOS apps, the same 400-connector surface, and a sandboxed cloud environment, with optional iPhone remote-approval. **1Password Unified Access** ([April 30, 2026 partnership](https://1password.com/blog/1password-and-perplexity-expand-partnership)) provides dynamic credential provisioning for Computer without exposing secrets to the model — relevant infrastructure for connector-heavy workflows, not a discrete connector itself.

For more information, see the [Perplexity Connectors Help Center](https://www.perplexity.ai/help-center/en/collections/18799295-connectors-integrations), the [App Connectors directory](https://www.perplexity.ai/help-center/en/collections/15347354-app-connectors), and the [Local and Remote MCPs documentation](https://www.perplexity.ai/help-center/en/articles/local-and-remote-mcps).

**Legend:** 💎 Premium-tier required · 🎖️ Perplexity-internal connector (no external vendor surface).

> This is an independent, community-maintained list. Not affiliated with, endorsed by, or sponsored by Perplexity AI, Inc. "Perplexity" and related marks are the property of Perplexity AI, Inc. Each connector is the property of its respective owner.

---

## Contents

- [Communication and Email](#communication-and-email)
- [Customer Support and CRM](#customer-support-and-crm)
- [Data and Analytics](#data-and-analytics)
- [Development Tools](#development-tools)
- [Documents and Files](#documents-and-files)
- [Finance and Investing](#finance-and-investing)
- [Healthcare and Life Sciences](#healthcare-and-life-sciences)
- [Legal](#legal)
- [Lifestyle and Local](#lifestyle-and-local)
- [Productivity and Notes](#productivity-and-notes)
- [Project Management](#project-management)
- [Research and Data](#research-and-data)

## Communication and Email

- [Gmail with Calendar](https://mail.google.com) - Search and act on email and calendar events. *Use case: Drafting replies grounded in thread history, scheduling around existing commitments, summarizing inbox state without opening Gmail.*
- [Microsoft Teams](https://www.microsoft.com/en-us/microsoft-teams/group-chat-software) - Search and send messages across chats and channels. *Use case: Cross-channel message search, posting status updates, summarizing channel activity.*
- [Outlook](https://outlook.com) - Search emails and calendar events. *Use case: Email triage in Microsoft 365 environments, calendar coordination across Outlook on the Web and outlook.com.*
- [Slack](https://slack.com) - Search and post messages across your workspace. *Use case: Workspace-wide search beyond a single channel, posting messages from a research session, surfacing buried decisions in long threads.*

## Customer Support and CRM

- [HubSpot](https://www.hubspot.com) - Retrieve, create, and update CRM objects; manage contacts, companies, deals, tasks, and notes. *Use case: Enriching deal records from research, logging contact notes from a call summary, querying pipeline state in natural language.*
- [Intercom](https://www.intercom.com) - Search conversations and contacts; retrieve customer data, support tickets, and user profiles. *Use case: Pulling conversation history for a customer, summarizing recurring support themes, accessing user profile context during research.*
- [Shopify](https://www.shopify.com) - Manage products, orders, customers, inventory, and store operations. *Use case: Querying order state, updating inventory from a sourcing decision, surfacing customer order history during support workflows.*

## Data and Analytics

- [Databricks](https://www.databricks.com) - Query live lakehouse data, explore tables, and turn results into cited reports. Native AI data agent in Computer; admin-managed semantic-layer permissions. *Use case: Natural-language warehouse queries, cross-table joins for analysis, generating exportable cited reports without manual SQL exports. Joined Computer May 4, 2026.*
- [Snowflake](https://www.snowflake.com) - Query live Snowflake warehouse data with semantic-layer awareness; results cited and exportable. *Use case: Plain-English BI against governed Snowflake data, ad-hoc analysis without notebooks, semantic-layer edits reviewed by admins before commit. Joined Computer May 4, 2026.*

## Development Tools

- [GitHub](https://github.com) - Search and manage repositories. *Use case: Repository-wide code search, PR/issue triage, pulling commit context into a research thread.*
- [Jam](https://jam.dev) - Access bug recordings with video, console logs, errors, network requests, and user events; create comments and manage issue tracking. *Use case: Triaging customer-reported bugs with full technical context, summarizing recurring failure modes across captured sessions.*
- [Lucid](https://lucid.co) - Ideate, diagram, and align teams (Lucidchart and Lucidspark). *Use case: Generating architecture diagrams during a design session, reading existing whiteboards into a research thread, building visuals from data sources.*
- [Stytch](https://stytch.com) - Authenticate and secure users, unifying login, authorization, and fraud protection for modern apps. *Use case: Querying auth events and user identity state, debugging login flows, reviewing fraud verdicts during incident response.*
- [Supabase](https://supabase.com) - Build and manage your app's database, auth, and storage. *Use case: Querying PostgreSQL tables in natural language, inspecting auth state, managing storage buckets without leaving the assistant.*
- [Vercel](https://vercel.com) - Manage teams, projects, and deployments; search documentation and control infrastructure. *Use case: Checking deployment state, debugging build failures, querying analytics, controlling project config from a research thread.*

## Documents and Files

- [Box](https://www.box.com) - Get in-depth answers from Box content. *Use case: Cross-document search across Box-stored content, summarizing folders of files, pulling Box artifacts into a research thread.*
- [Dropbox](https://www.dropbox.com) - Get in-depth answers from Dropbox content. *Use case: Searching Dropbox-stored documents from natural-language queries, surfacing answers from PDFs and spreadsheets without opening Dropbox.*
- [Google Drive](https://drive.google.com) - Get in-depth answers from Google Drive content. *Use case: Searching across Docs/Sheets/Slides, summarizing entire folders, citing Drive-hosted artifacts in research output.*
- [OneDrive](https://onedrive.live.com) - Get in-depth answers from OneDrive content. *Use case: Microsoft 365 file retrieval, summarizing Office documents, querying OneDrive content alongside web sources.*
- [SharePoint](https://www.microsoft.com/en-us/microsoft-365/sharepoint/collaboration) - Get in-depth answers from SharePoint content. *Use case: Enterprise document search across SharePoint sites, retrieving policy/procedure docs, summarizing site content for stakeholders.*

## Finance and Investing

- [Carbon Arc](https://carbonarc.ai) - Real-time transaction data insights and entity analytics. *Use case: Querying consumption-based data assets in natural language, building cohorts and entity analytics, surfacing transaction trends without dedicated data engineering.*
- [CB Insights](https://www.cbinsights.com) - Search market insights, market maps, and company activity. *Use case: Competitive intelligence on private companies, tracking funding rounds and partnerships, market-map research during diligence.*
- [Investment Portfolio](https://plaid.com) - View investment holdings, transactions, and liabilities — powered by Plaid. *Use case: Querying portfolio composition, surfacing recent transactions, computing exposure across linked accounts.*
- [Morningstar](https://www.morningstar.com) - Access financial data, stock metrics, fund ratings, and investment research. *Use case: Equity and fund research, screening by Morningstar ratings, pulling fundamentals into investment workflows.*
- [PitchBook](https://pitchbook.com) - Search firmographics for private and public companies. *Use case: Private-company research, ownership and funding history, comparing portfolio companies during diligence.*

## Healthcare and Life Sciences

- [The BMJ](https://www.bmj.com) - International medical journal and healthcare knowledge platform. *Use case: Evidence retrieval for clinical questions, accessing investigations and policy commentary, citing peer-reviewed BMJ research in clinical reasoning.*
- [Function Health](https://www.functionhealth.com) - Personalized health insights from your Function Health membership labs. *Use case: Querying your own lab trends across the 100+ test panels, surfacing flagged biomarkers, contextualizing follow-up labs against baseline.*
- 🎖️ [Health and Fitness Apps](https://www.perplexity.ai/computer/connectors) - Securely connect health apps and wearables for personalized health insights. *Use case: Cross-source health data analysis (HRV, sleep, activity, nutrition), tracking trends across multiple apps, contextualizing wearable data with clinical questions.*
- 🎖️ [Medical Records](https://www.perplexity.ai) - Get personalized answers and plans using your health records. *Use case: Querying your own records, summarizing visit history, surfacing relevant prior diagnoses or labs during a clinical question.*
- [NEJM](https://www.nejm.org) - The New England Journal of Medicine — peer-reviewed clinical research and education. *Use case: Citing seminal trial evidence in clinical reasoning, accessing case-based education, sourcing rigorous medical research grounded in NEJM's editorial standard.*

## Legal

- [Midpage](https://www.midpage.ai) - A law library for AI — search, analyze, and cite US case law with confidence. *Use case: Drafting briefs and memos with hyperlinked citations to real opinions, cite-checking drafts, finding cases by fact pattern across federal and state courts.*

## Lifestyle and Local

- [DoorDash](https://www.doordash.com) - Manage deliveries, quotes, businesses, stores, and address lookup. *Use case: Ordering food via natural language, querying delivery status, accessing business and address data for logistics workflows.*

## Productivity and Notes

- [Notion](https://www.notion.so) - Search and create content across your workspace. *Use case: Workspace-wide search, creating new pages from research output, updating databases and properties from natural-language commands.*
- [Todoist](https://todoist.com) - Task planner and to-do list. *Use case: Adding tasks from a research session, querying due-date pressure across projects, summarizing weekly task load.*

## Project Management

- [Asana](https://asana.com) - Plan and track projects, tasks, and team workflows. *Use case: Creating tasks from meeting notes, querying project status, surfacing dependencies and blockers across teams.*
- [Confluence](https://www.atlassian.com/software/confluence) - Search and create wiki content across spaces. *Use case: Enterprise wiki search, drafting new pages from research output, summarizing space activity for stakeholders.*
- [Jira](https://www.atlassian.com/software/jira) - Plan and track projects, tasks, and team workflows. *Use case: Issue triage, sprint planning, querying status across projects, creating tickets from natural-language descriptions.*
- [Linear](https://linear.app) - Plan and track projects, issues, and team workflows. *Use case: Issue management for engineering teams, cycle planning, surfacing in-flight work across projects.*
- [Monday.com](https://monday.com) - Manage boards, items, and groups; create updates and sub-items; automate project workflows. *Use case: Cross-board project queries, updating item status from research output, automating routine task creation.*

## Research and Data

- 💎 [Statista](https://www.statista.com) - Market and consumer data. *Use case: Market sizing, consumer behavior research, sourcing statistics with attribution for reports and presentations.*
- [Wiley](https://onlinelibrary.wiley.com) - Academic research and publications across disciplines. *Use case: Accessing peer-reviewed journal articles, citing Wiley-published research in academic and clinical work.*

## Contributing

Contributions are welcome — see [CONTRIBUTING.md](CONTRIBUTING.md) for the submission flow, tier-tracking conventions (Computer / Pro / Enterprise), and the entry style guide. By contributing you agree to the [Code of Conduct](code-of-conduct.md).
