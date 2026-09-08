# Awesome MCP Servers

> A curated catalog of **Model Context Protocol (MCP)** servers — official, community-built, and production-ready — organized by category to help you find the right integration fast.

The **[Model Context Protocol](https://modelcontextprotocol.io)** is an open standard (introduced by Anthropic) that lets AI applications securely connect to external tools, data sources, and services. MCP servers expose **tools**, **resources**, and **prompts** that clients like Claude Desktop, VS Code (GitHub Copilot), Cursor, Windsurf, Zed, and others can use.

---

## Table of Contents

- [Official Reference Servers](#official-reference-servers)
- [Developer Tools](#developer-tools)
- [Databases](#databases)
- [Cloud & Infrastructure](#cloud--infrastructure)
- [Kubernetes & DevOps](#kubernetes--devops)
- [Productivity & Collaboration](#productivity--collaboration)
- [Communication](#communication)
- [Search & Web](#search--web)
- [Browser Automation](#browser-automation)
- [File Systems & Storage](#file-systems--storage)
- [AI, ML & Data](#ai-ml--data)
- [CRM & Business](#crm--business)
- [Design & Creative](#design--creative)
- [Finance & Payments](#finance--payments)
- [Media & Content](#media--content)
- [Monitoring & Observability](#monitoring--observability)
- [Version Control](#version-control)
- [Security](#security)
- [Frameworks & SDKs](#frameworks--sdks)
- [MCP Clients](#mcp-clients)
- [Learning Resources](#learning-resources)
- [Contributing](#contributing)

---

## Official Reference Servers

Maintained by the MCP core team at [modelcontextprotocol/servers](https://github.com/modelcontextprotocol/servers).

| Server | Description |
|---|---|
| [Everything](https://github.com/modelcontextprotocol/servers/tree/main/src/everything) | Reference/test server demonstrating all MCP features (prompts, resources, tools). |
| [Fetch](https://github.com/modelcontextprotocol/servers/tree/main/src/fetch) | Web content fetching and conversion for LLM usage. |
| [Filesystem](https://github.com/modelcontextprotocol/servers/tree/main/src/filesystem) | Secure file operations with configurable access controls. |
| [Git](https://github.com/modelcontextprotocol/servers/tree/main/src/git) | Read, search, and manipulate Git repositories. |
| [Memory](https://github.com/modelcontextprotocol/servers/tree/main/src/memory) | Knowledge graph-based persistent memory. |
| [Sequential Thinking](https://github.com/modelcontextprotocol/servers/tree/main/src/sequentialthinking) | Dynamic problem-solving through structured thought sequences. |
| [Time](https://github.com/modelcontextprotocol/servers/tree/main/src/time) | Time and timezone conversion utilities. |

---

## Developer Tools

| Server | Description |
|---|---|
| [GitHub](https://github.com/github/github-mcp-server) | Official GitHub MCP — repos, issues, PRs, actions, code search. |
| [GitLab](https://github.com/modelcontextprotocol/servers-archived/tree/main/src/gitlab) | GitLab API integration for project management. |
| [Sentry](https://github.com/getsentry/sentry-mcp) | Retrieve and analyze issues from Sentry.io. |
| [JetBrains](https://github.com/JetBrains/mcp-jetbrains) | Work with any JetBrains IDE. |
| [VS Code](https://code.visualstudio.com/docs/copilot/chat/mcp-servers) | VS Code exposes an MCP server for editor context and actions. |
| [Xcode](https://github.com/cameroncooke/XcodeBuildMCP) | Build, test, and manage Xcode projects. |
| [Docker](https://github.com/docker/mcp-servers) | Docker's collection of MCP servers (compose, hub, etc.). |
| [npm](https://github.com/npm-mcp/npm-mcp-server) | Query npm registry, packages, versions. |
| [Package Version](https://github.com/sammcj/mcp-package-version) | Check latest versions across npm, PyPI, Maven, etc. |

---

## Databases

| Server | Description |
|---|---|
| [PostgreSQL](https://github.com/modelcontextprotocol/servers-archived/tree/main/src/postgres) | Read-only DB access with schema inspection. |
| [SQLite](https://github.com/modelcontextprotocol/servers-archived/tree/main/src/sqlite) | Query and analyze SQLite databases. |
| [MySQL](https://github.com/benborla/mcp-server-mysql) | Query MySQL databases with configurable access. |
| [MongoDB](https://github.com/mongodb-js/mongodb-mcp-server) | Official MongoDB MCP server. |
| [Redis](https://github.com/redis/mcp-redis) | Official Redis MCP for keys, streams, and search. |
| [Elasticsearch](https://github.com/elastic/mcp-server-elasticsearch) | Query and inspect Elasticsearch indices. |
| [ClickHouse](https://github.com/ClickHouse/mcp-clickhouse) | Query and analyze ClickHouse databases. |
| [Snowflake](https://github.com/isaacwasserman/mcp-snowflake-server) | Query Snowflake data warehouses. |
| [BigQuery](https://github.com/LucasHild/mcp-server-bigquery) | Query Google BigQuery. |
| [Databricks](https://github.com/JustTryAI/databricks-mcp-server) | Interact with Databricks workspaces and jobs. |
| [Neo4j](https://github.com/neo4j-contrib/mcp-neo4j) | Graph queries via Cypher. |
| [DuckDB](https://github.com/ktanaka101/mcp-server-duckdb) | Analytical queries with DuckDB. |
| [Supabase](https://github.com/supabase-community/supabase-mcp) | Manage Supabase projects, DBs, edge functions. |
| [PlanetScale](https://github.com/planetscale/mcp-planetscale) | MySQL-compatible serverless DB. |
| [Turso](https://github.com/tursodatabase/mcp-turso-cloud) | libSQL/Turso edge DB. |

---

## Cloud & Infrastructure

| Server | Description |
|---|---|
| [AWS Labs](https://github.com/awslabs/mcp) | Official AWS MCP servers (CDK, docs, Bedrock KB, cost analyzer, and more). |
| [AWS KB Retrieval](https://github.com/modelcontextprotocol/servers-archived/tree/main/src/aws-kb-retrieval-server) | Retrieval from Bedrock Knowledge Bases. |
| [Azure](https://github.com/Azure/azure-mcp) | Official Azure MCP — resource management and diagnostics. |
| [Google Cloud](https://github.com/GoogleCloudPlatform/genai-toolbox) | GCP toolbox for GenAI workloads (includes MCP). |
| [Cloudflare](https://github.com/cloudflare/mcp-server-cloudflare) | Manage Workers, KV, R2, D1, Zones. |
| [Terraform](https://github.com/hashicorp/terraform-mcp-server) | HashiCorp's official Terraform MCP. |
| [Vercel](https://vercel.com/docs/mcp/vercel-mcp) | Manage Vercel deployments and projects. |
| [Netlify](https://docs.netlify.com/build/build-with-ai/netlify-mcp-server/) | Manage Netlify sites and deployments. |
| [Railway](https://github.com/jason-tan/railway-mcp) | Railway.app project management. |
| [Fly.io](https://github.com/superfly/mcp-fly) | Manage Fly.io applications. |

---

## Kubernetes & DevOps

| Server | Description |
|---|---|
| [Kubernetes](https://github.com/Flux159/mcp-server-kubernetes) | Manage clusters — pods, deployments, services, logs. |
| [k8s-mcp-server](https://github.com/alexei-led/k8s-mcp-server) | Execute kubectl, helm, istioctl, argocd. |
| [Helm](https://github.com/zekker6/mcp-helm) | Manage Helm releases and charts. |
| [ArgoCD](https://github.com/akuity/mcp-server-argocd) | GitOps continuous delivery. |
| [Prometheus](https://github.com/pab1it0/prometheus-mcp-server) | Query Prometheus metrics. |
| [Grafana](https://github.com/grafana/mcp-grafana) | Official Grafana MCP for dashboards and datasources. |
| [Jenkins](https://github.com/lanbaoshen/jenkins-mcp) | Trigger and monitor Jenkins builds. |
| [GitHub Actions](https://github.com/ko1ynnky/github-actions-mcp-server) | Manage and inspect workflow runs. |

---

## Productivity & Collaboration

| Server | Description |
|---|---|
| [Notion](https://github.com/makenotion/notion-mcp-server) | Official Notion MCP — pages, DBs, blocks. |
| [Linear](https://linear.app/docs/mcp) | Official Linear MCP for issues and projects. |
| [Jira](https://github.com/sooperset/mcp-atlassian) | Atlassian MCP — Jira + Confluence. |
| [Confluence](https://github.com/sooperset/mcp-atlassian) | Wikis, spaces, pages. |
| [Asana](https://developers.asana.com/docs/mcp) | Official Asana MCP. |
| [Trello](https://github.com/delorenj/mcp-server-trello) | Board, list, and card management. |
| [Todoist](https://github.com/abhiz123/todoist-mcp-server) | Task management. |
| [ClickUp](https://github.com/taazkareem/clickup-mcp-server) | Project and task management. |
| [Obsidian](https://github.com/MarkusPfundstein/mcp-obsidian) | Read and edit Obsidian vaults. |
| [Airtable](https://github.com/domdomegg/airtable-mcp-server) | Read/write Airtable bases. |
| [Monday.com](https://github.com/mondaycom/mcp) | Official Monday.com MCP. |

---

## Communication

| Server | Description |
|---|---|
| [Slack](https://github.com/modelcontextprotocol/servers-archived/tree/main/src/slack) | Post messages, manage channels. |
| [Discord](https://github.com/v-3/discordmcp) | Discord bot integrations. |
| [Microsoft Teams](https://github.com/InditexTech/mcp-teams-server) | Teams messaging and channels. |
| [Telegram](https://github.com/chigwell/telegram-mcp) | Telegram bot integration. |
| [WhatsApp](https://github.com/lharries/whatsapp-mcp) | WhatsApp via personal account. |
| [Gmail](https://github.com/GongRzhe/Gmail-MCP-Server) | Read/send email via Gmail. |
| [Outlook](https://github.com/ryaker/outlook-mcp) | Microsoft Outlook mail/calendar. |
| [Resend](https://github.com/resend/mcp-send-email) | Send transactional email. |

---

## Search & Web

| Server | Description |
|---|---|
| [Brave Search](https://github.com/modelcontextprotocol/servers-archived/tree/main/src/brave-search) | Web and local search via Brave API. |
| [Tavily](https://github.com/tavily-ai/tavily-mcp) | AI-native search and extract. |
| [Exa](https://github.com/exa-labs/exa-mcp-server) | Neural web search. |
| [Perplexity](https://github.com/ppl-ai/modelcontextprotocol) | Ask Perplexity's Sonar models. |
| [DuckDuckGo](https://github.com/nickclyde/duckduckgo-mcp-server) | Privacy-focused web search. |
| [Kagi](https://github.com/kagisearch/kagimcp) | Official Kagi search MCP. |
| [SerpAPI](https://github.com/ilyazub/serpapi-mcp-server) | SERP data from Google, Bing, and more. |
| [Wikipedia](https://github.com/rudra-ravi/wikipedia-mcp) | Query Wikipedia articles. |
| [arXiv](https://github.com/blazickjp/arxiv-mcp-server) | Search academic papers. |
| [Firecrawl](https://github.com/mendableai/firecrawl-mcp-server) | Scrape and crawl any website. |

---

## Browser Automation

| Server | Description |
|---|---|
| [Agent QA](https://github.com/vostride/agent-qa) | Runs natural-language web and mobile regression tests with retained execution evidence. |
| [Playwright](https://github.com/microsoft/playwright-mcp) | Official Microsoft Playwright MCP. |
| [Puppeteer](https://github.com/modelcontextprotocol/servers-archived/tree/main/src/puppeteer) | Browser automation and scraping. |
| [Browser Use](https://github.com/browser-use/browser-use) | AI-driven browser control. |
| [Browserbase](https://github.com/browserbase/mcp-server-browserbase) | Cloud browser sessions. |
| [Apify](https://github.com/apify/actors-mcp-server) | 3,000+ web scraping actors. |

---

## File Systems & Storage

| Server | Description |
|---|---|
| [Google Drive](https://github.com/modelcontextprotocol/servers-archived/tree/main/src/gdrive) | Access and search Google Drive files. |
| [Dropbox](https://github.com/AudienceCloud/dropbox-mcp-server) | Read/write Dropbox files. |
| [OneDrive](https://github.com/xxxbrian/mcp-onedrive) | Microsoft OneDrive integration. |
| [S3](https://github.com/aws-samples/sample-mcp-server-s3) | Amazon S3 bucket operations. |
| [Box](https://github.com/box-community/mcp-server-box) | Official Box integration. |
| [Excel MCP Server](https://github.com/haris-musa/excel-mcp-server) | Read and manipulate Excel workbooks. |
| [PDF Reader](https://github.com/gpetraroli/mcp_pdf_reader) | Extract text and structure from PDFs. |

---

## AI, ML & Data

| Server | Description |
|---|---|
| [HuggingFace](https://github.com/evalstate/mcp-hfspace) | Interact with HF Spaces. |
| [Replicate](https://github.com/deepfates/mcp-replicate) | Run models on Replicate. |
| [OpenAI](https://github.com/pierrebrunelle/mcp-server-openai) | Query OpenAI models directly. |
| [RunAPI](https://github.com/runapi-ai/mcp) | Run AI image, video, music, audio, and LLM jobs through one MCP server. |
| [Ollama](https://github.com/rawveg/ollama-mcp) | Local LLMs via Ollama. |
| [Pinecone](https://github.com/sirmews/mcp-pinecone) | Vector database queries. |
| [Weaviate](https://github.com/weaviate/mcp-server-weaviate) | Vector database with hybrid search. |
| [Qdrant](https://github.com/qdrant/mcp-server-qdrant) | Semantic memory in Qdrant. |
| [Chroma](https://github.com/chroma-core/chroma-mcp) | Chroma vector DB integration. |
| [LangSmith](https://github.com/langchain-ai/langsmith-mcp-server) | LangChain tracing and evals. |

---

## CRM & Business

| Server | Description |
|---|---|
| [HubSpot](https://github.com/HubSpot/mcp-server-hubspot) | Official HubSpot MCP for contacts, deals, tickets. |
| [Salesforce](https://github.com/kablewy/salesforce-mcp-server) | CRM object queries and updates. |
| [Intercom](https://github.com/raoulbia-ai/mcp-server-for-intercom) | Customer conversations and users. |
| [Zendesk](https://github.com/reminia/zendesk-mcp-server) | Tickets and customer support. |
| [Shopify](https://github.com/Shopify/dev-mcp) | Official Shopify Dev MCP. |
| [Stripe](https://github.com/stripe/agent-toolkit) | Payments, customers, invoices. |
| [Square](https://github.com/square/square-mcp-server) | Payments and commerce APIs. |

---

## Design & Creative

| Server | Description |
|---|---|
| [Figma](https://github.com/GLips/Figma-Context-MCP) | Read Figma designs into AI context. |
| [Blender](https://github.com/ahujasid/blender-mcp) | Control Blender for 3D modeling. |
| [EverArt](https://github.com/modelcontextprotocol/servers-archived/tree/main/src/everart) | AI image generation. |
| [Canva](https://www.canva.dev/docs/apps/mcp-server/) | Official Canva MCP for designs. |

---

## Finance & Payments

| Server | Description |
|---|---|
| [Stripe](https://github.com/stripe/agent-toolkit) | Payments and billing. |
| [Plaid](https://github.com/hellozukun/plaid-mcp) | Banking data via Plaid. |
| [PayPal](https://mcp.paypal.com/) | Official PayPal MCP. |
| [Alpaca](https://github.com/alpacahq/alpaca-mcp-server) | Trade stocks and crypto. |
| [CoinGecko](https://github.com/coingecko/coingecko-mcp) | Crypto market data. |
| [Yahoo Finance](https://github.com/maxscheijen/mcp-yahoo-finance) | Stock quotes and financials. |

---

## Media & Content

| Server | Description |
|---|---|
| [YouTube](https://github.com/anaisbetts/mcp-youtube) | Transcripts and metadata. |
| [Spotify](https://github.com/varunneal/spotify-mcp) | Control playback, query catalog. |
| [Reddit](https://github.com/adhikasp/mcp-reddit) | Fetch posts and comments. |
| [Twitter/X](https://github.com/EnesCinr/twitter-mcp) | Read and post tweets. |
| [Bluesky](https://github.com/berrydev-ai/bsky-social-mcp) | AT Protocol integration. |
| [OrkasVideoStudio](https://github.com/Orkas-AI/Orkas-VideoStudio) | Local video composition and editing via MCP and editable plan.json timelines. |
| [Unsplash](https://github.com/hellokaton/unsplash-mcp-server) | Free stock photo search. |

---

## Monitoring & Observability

| Server | Description |
|---|---|
| [Datadog](https://github.com/GeLi2001/datadog-mcp-server) | Metrics, logs, monitors. |
| [Grafana](https://github.com/grafana/mcp-grafana) | Dashboards and data sources. |
| [Prometheus](https://github.com/pab1it0/prometheus-mcp-server) | PromQL queries. |
| [Sentry](https://github.com/getsentry/sentry-mcp) | Error tracking. |
| [Honeycomb](https://github.com/honeycombio/honeycomb-mcp) | Observability queries. |
| [PagerDuty](https://github.com/wpfleger96/pagerduty-mcp-server) | Incident management. |

---

## Version Control

| Server | Description |
|---|---|
| [GitHub](https://github.com/github/github-mcp-server) | Repos, PRs, issues, actions. |
| [GitLab](https://github.com/modelcontextprotocol/servers-archived/tree/main/src/gitlab) | GitLab project management. |
| [Bitbucket](https://github.com/aashari/mcp-server-atlassian-bitbucket) | Atlassian Bitbucket. |
| [Gitea](https://github.com/gitea/gitea-mcp) | Self-hosted Git integration. |

---

## Security

| Server | Description |
|---|---|
| [Semgrep](https://github.com/semgrep/mcp) | Static analysis for security. |
| [Snyk](https://github.com/snyk/snyk-ls) | Vulnerability scanning (LSP + MCP). |
| [1Password](https://developer.1password.com/docs/mcp/) | Official 1Password MCP for secrets. |
| [HashiCorp Vault](https://github.com/ashgw/vault-mcp) | Secret management. |
| [Shodan](https://github.com/BurtTheCoder/mcp-shodan) | Internet-connected device search. |

---

## Frameworks & SDKs

Build your own MCP server.

| SDK | Language |
|---|---|
| [TypeScript SDK](https://github.com/modelcontextprotocol/typescript-sdk) | TypeScript / Node.js |
| [Python SDK](https://github.com/modelcontextprotocol/python-sdk) | Python |
| [Java SDK](https://github.com/modelcontextprotocol/java-sdk) | Java |
| [C# SDK](https://github.com/modelcontextprotocol/csharp-sdk) | C# / .NET |
| [Kotlin SDK](https://github.com/modelcontextprotocol/kotlin-sdk) | Kotlin |
| [Swift SDK](https://github.com/modelcontextprotocol/swift-sdk) | Swift |
| [Rust SDK](https://github.com/modelcontextprotocol/rust-sdk) | Rust |
| [Go SDK](https://github.com/modelcontextprotocol/go-sdk) | Go |
| [FastMCP](https://github.com/jlowin/fastmcp) | High-level Python framework |
| [mcp-framework](https://github.com/QuantGeekDev/mcp-framework) | TypeScript framework |

---

## MCP Clients

Applications that consume MCP servers.

| Client | Description |
|---|---|
| [Claude Desktop](https://claude.ai/download) | Anthropic's official desktop app. |
| [Claude Code](https://docs.anthropic.com/en/docs/claude-code) | Anthropic's CLI coding agent. |
| [VS Code (GitHub Copilot)](https://code.visualstudio.com/docs/copilot/chat/mcp-servers) | Copilot Chat with MCP support. |
| [Cursor](https://docs.cursor.com/context/model-context-protocol) | AI code editor. |
| [Windsurf](https://docs.codeium.com/windsurf/mcp) | Codeium's agentic IDE. |
| [Zed](https://zed.dev/docs/assistant/model-context-protocol) | High-performance editor. |
| [Continue](https://docs.continue.dev/customize/deep-dives/mcp) | Open-source IDE assistant. |
| [Cline](https://github.com/cline/cline) | Autonomous coding agent for VS Code. |
| [LibreChat](https://www.librechat.ai/docs/features/mcp) | Open-source ChatGPT alternative. |
| [Goose](https://github.com/block/goose) | Block's open-source AI agent. |

---

## Learning Resources

- **Spec:** [modelcontextprotocol.io/specification](https://modelcontextprotocol.io/specification)
- **Introduction:** [modelcontextprotocol.io/introduction](https://modelcontextprotocol.io/introduction)
- **Anthropic MCP announcement:** [anthropic.com/news/model-context-protocol](https://www.anthropic.com/news/model-context-protocol)
- **Awesome MCP Servers:** [github.com/punkpeye/awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers)
- **MCP Registry:** [github.com/modelcontextprotocol/registry](https://github.com/modelcontextprotocol/registry)
- **Debugging guide:** [modelcontextprotocol.io/docs/tools/debugging](https://modelcontextprotocol.io/docs/tools/debugging)
- **Inspector tool:** [github.com/modelcontextprotocol/inspector](https://github.com/modelcontextprotocol/inspector)

---

## Contributing

Contributions are welcome! See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

Quick checklist:
1. Keep entries alphabetical within categories where possible.
2. Include a working link and a one-line description.
3. Prefer official servers when available.
4. Verify the server actually exists and is maintained.

---

## License

[MIT](LICENSE) — free to use, share, and adapt.

---

<sub>⭐ If you find this useful, please star the repo to help others discover it.</sub>
