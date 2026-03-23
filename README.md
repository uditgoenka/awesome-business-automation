<!--lint disable awesome-heading-->
<div align="center">

<!-- title -->

# Awesome Business Automation [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<!-- subtitle -->

A curated list of tools, frameworks, and resources for automating real business operations with AI. Bridges the gap between AI agent frameworks and practical business use cases.

<!-- image -->

<!-- description -->

Unlike developer-focused lists or stale workflow directories, this list connects **tools to practical business outcomes** — from lead nurturing and invoice generation to property management and compliance automation.

</div>

<!-- toc -->

## Contents

- [Workflow Automation Platforms](#workflow-automation-platforms)
- [AI Agent Frameworks](#ai-agent-frameworks)
- [CRM and Sales Automation](#crm-and-sales-automation)
- [Marketing Automation](#marketing-automation)
- [MCP Servers for Business](#mcp-servers-for-business)
- [Video and Content Automation](#video-and-content-automation)
- [Property Management and Hospitality](#property-management-and-hospitality)
- [Knowledge Management and Second Brain](#knowledge-management-and-second-brain)
- [Data and Analytics](#data-and-analytics)
- [Communication and Messaging](#communication-and-messaging)
- [Financial and Invoicing](#financial-and-invoicing)
- [Scheduling and Calendar](#scheduling-and-calendar)
- [Project Management](#project-management)
- [Compliance and Document Management](#compliance-and-document-management)
- [Curated Lists and Resources](#curated-lists-and-resources)

<!-- content -->

## Workflow Automation Platforms

Visual and code-based platforms for connecting business tools, building automations, and orchestrating multi-step workflows.

- [n8n-io/n8n](https://github.com/n8n-io/n8n) — Fair-code workflow automation platform with 400+ integrations and native AI agent capabilities. Self-hostable with a visual builder.
- [langgenius/dify](https://github.com/langgenius/dify) — Production-ready agentic AI workflow platform with visual builder, RAG pipelines, and agent orchestration.
- [activepieces/activepieces](https://github.com/activepieces/activepieces) — Open-source no-code business automation alternative to Zapier with 400+ MCP server integrations.
- [automatisch/automatisch](https://github.com/automatisch/automatisch) — Open-source Zapier alternative for building workflow automation without spending time and money.

## AI Agent Frameworks

Frameworks for building autonomous AI agents that can execute multi-step business tasks, reason about decisions, and interact with external tools.

- [langchain-ai/langchain](https://github.com/langchain-ai/langchain) — The agent engineering platform for developing AI-powered applications, chains, and autonomous agents.
- [crewAIInc/crewAI](https://github.com/crewAIInc/crewAI) — Multi-agent AI framework for orchestrating role-playing, autonomous AI agents that collaborate on complex tasks.
- [microsoft/autogen](https://github.com/microsoft/autogen) — Framework for building multi-agent conversational AI systems with programmable agent interactions.
- [block/goose](https://github.com/block/goose) — Open-source extensible AI agent that goes beyond code suggestions — install, execute, edit, and test with any LLM.
- [TransformerOptimus/SuperAGI](https://github.com/TransformerOptimus/SuperAGI) — Dev-first open-source autonomous AI agent framework for building, managing, and running useful agents.

## CRM and Sales Automation

Open-source and extensible CRM platforms for managing customer relationships, sales pipelines, and support operations.

- [maxtron777/awesome-gohighlevel](https://github.com/maxtron777/awesome-gohighlevel) — Curated list of GoHighLevel tools, integrations, SDKs, MCP servers, and resources for CRM automation.
- [twentyhq/twenty](https://github.com/twentyhq/twenty) — Open-source CRM alternative to Salesforce, built with a modern stack and community-driven development.
- [erxes/erxes](https://github.com/erxes/erxes) — Open-source experience operating system that unifies marketing, sales, operations, and support in one platform.
- [chatwoot/chatwoot](https://github.com/chatwoot/chatwoot) — Open-source customer engagement suite with live-chat, email support, and omni-channel desk. An alternative to Intercom and Zendesk.

## Marketing Automation

Tools for automating email campaigns, lead nurturing, social media scheduling, and marketing analytics.

- [maxtron777/n8n-ai-business-workflows](https://github.com/maxtron777/n8n-ai-business-workflows) — Production-ready n8n workflows combining AI with real business automation — lead scoring, client onboarding, SEO monitoring, and email triage.
- [mautic/mautic](https://github.com/mautic/mautic) — Open-source marketing automation platform for email campaigns, landing pages, lead scoring, and contact management.
- [knadh/listmonk](https://github.com/knadh/listmonk) — High-performance self-hosted newsletter and mailing list manager. Single binary app with a modern dashboard.

## MCP Servers for Business

The [Model Context Protocol (MCP)](https://modelcontextprotocol.io/) is an open standard from Anthropic that lets AI models interact with external tools and data sources. MCP servers turn business platforms into AI-accessible resources — enabling agents to manage CRM records, send emails, query databases, and more.

- [punkpeye/awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) — Comprehensive collection of MCP servers covering CRM, databases, communication platforms, and developer tools.
- [mastanley13/GoHighLevel-MCP](https://github.com/mastanley13/GoHighLevel-MCP) — MCP server for GoHighLevel CRM automation via AI — manage contacts, pipelines, and workflows through natural language.
- [supabase/mcp](https://github.com/supabase/mcp) — Official Supabase MCP server for database automation, enabling AI agents to query, insert, and manage data.

> **Tip:** Browse [Anthropic's MCP documentation](https://modelcontextprotocol.io/introduction) for the full specification and server development guides.

## Video and Content Automation

Programmatic video creation and content generation tools for scaling marketing output without manual editing.

- [remotion-dev/remotion](https://github.com/remotion-dev/remotion) — Make videos programmatically with React. Build branded video templates that render dynamically with data.
- [redotvideo/revideo](https://github.com/redotvideo/revideo) — Create videos with code. A streamlined approach to programmatic video generation.

## Property Management and Hospitality

> **Note:** This is an emerging area for open-source automation. Most property management tooling remains proprietary, but API-first platforms are enabling custom integrations.

**API-first platforms with automation potential:**

- [Guesty API](https://developer.guesty.com/) — Short-term rental management platform with a comprehensive API for booking, guest communication, and channel management.
- [PriceLabs](https://pricelabs.co/) — Dynamic pricing and revenue management with API access for automated rate optimisation.
- [AirDNA](https://www.airdna.co/) — Short-term rental analytics and market data with API access for data-driven investment decisions.

> **Opportunity:** No mature open-source property management platform exists yet. This is a significant gap for the community to fill.

## Knowledge Management and Second Brain

Tools for building personal and organisational knowledge bases that integrate with AI agents for contextual retrieval and decision support.

- [khoj-ai/khoj](https://github.com/khoj-ai/khoj) — AI copilot for your second brain. Self-hostable, with answers from the web or your docs. Supports custom agents and scheduled automations.
- [logseq/logseq](https://github.com/logseq/logseq) — Privacy-first, open-source platform for knowledge management and collaboration with graph-based organisation.

> **Note:** Supabase-backed second brain implementations are emerging as a lightweight alternative — using PostgreSQL full-text search and vector embeddings for AI-powered knowledge retrieval.

## Data and Analytics

Open-source business intelligence, database, and analytics platforms for data-driven decision making.

- [metabase/metabase](https://github.com/metabase/metabase) — Open-source business intelligence and embedded analytics tool that lets everyone work with data through a visual query builder.
- [nocodb/nocodb](https://github.com/nocodb/nocodb) — Open-source Airtable alternative that turns any database into a smart spreadsheet with APIs, automations, and collaboration.
- [baserow/baserow](https://github.com/baserow/baserow) — Open-source no-code database platform for building databases, automations, apps, and agents with AI.

## Communication and Messaging

Open-source communication platforms for customer-facing messaging, team collaboration, and automated notifications.

- [chatwoot/chatwoot](https://github.com/chatwoot/chatwoot) — Open-source customer messaging platform with live-chat, email, and social media integration.
- [RocketChat/Rocket.Chat](https://github.com/RocketChat/Rocket.Chat) — Open-source communications platform for team messaging, video conferencing, and customer engagement.
- [element-hq/synapse](https://github.com/element-hq/synapse) — Matrix homeserver implementation enabling decentralised, end-to-end encrypted messaging for organisations.

## Financial and Invoicing

Open-source accounting, invoicing, and payment management tools for small businesses and freelancers.

- [invoiceninja/invoiceninja](https://github.com/invoiceninja/invoiceninja) — Source-available invoicing, quoting, project tracking, and time-tracking app built with Laravel.
- [crater-invoice/crater](https://github.com/crater-invoice/crater) — Open-source invoicing solution for individuals and small businesses with expense tracking and payment recording.
- [akaunting/akaunting](https://github.com/akaunting/akaunting) — Free online accounting software for small businesses with invoicing, expense tracking, and financial reporting.

## Scheduling and Calendar

Open-source scheduling infrastructure for appointment booking, availability management, and calendar automation.

- [calcom/cal.com](https://github.com/calcom/cal.com) — Open-source scheduling infrastructure for absolutely everyone. Self-hostable alternative to Calendly with team scheduling and integrations.

## Project Management

Open-source project management platforms for task tracking, sprint planning, and team coordination.

- [makeplane/plane](https://github.com/makeplane/plane) — Open-source project management alternative to Jira, Linear, Monday, and ClickUp with sprints, docs, and triage.
- [hcengineering/platform](https://github.com/hcengineering/platform) — Huly — all-in-one project management platform as an alternative to Linear, Jira, Slack, Notion, and Motion.

## Compliance and Document Management

Tools for digitising documents, managing compliance workflows, and automating document signing.

- [paperless-ngx/paperless-ngx](https://github.com/paperless-ngx/paperless-ngx) — Community-supported document management system for scanning, indexing, and archiving all your documents.
- [docusealco/docuseal](https://github.com/docusealco/docuseal) — Open-source DocuSign alternative for creating, filling, and signing digital documents.

## Curated Lists and Resources

Meta-lists and resource collections for discovering more business automation tools.

- [e2b-dev/awesome-ai-agents](https://github.com/e2b-dev/awesome-ai-agents) — Comprehensive list of AI autonomous agents covering frameworks, platforms, and research.
- [restyler/awesome-n8n](https://github.com/restyler/awesome-n8n) — Community-curated n8n nodes, workflows, and resources for extending workflow automation.
- [awesome-selfhosted/awesome-selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted) — Massive directory of self-hosted software spanning every business category.
- [maxtron777/awesome-gohighlevel](https://github.com/maxtron777/awesome-gohighlevel) — GoHighLevel tools, integrations, SDKs, and MCP servers for CRM and marketing automation.

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.
