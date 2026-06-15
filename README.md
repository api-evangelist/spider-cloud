# Spider (spider-cloud)

Spider is a Rust-based, AI-friendly web scraping and crawling cloud. Point it at a URL and get back clean markdown, structured JSON, screenshots, or links — at up to 100K pages per second — with anti-bot bypass, residential proxies, headless browsers, and native MCP, LangChain, LlamaIndex, CrewAI, and AutoGen integrations.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/spider-cloud/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/spider-cloud/refs/heads/main/apis.yml)

## Scope

- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Crawling
- Scraping
- Data Extraction
- URLs
- AI
- Markdown
- MCP
- Rust
- Headless Browser
- Proxies

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### Spider API

The Spider Cloud REST API exposes core /crawl, /scrape, /search, /links, /screenshot, /unblocker, and /transform endpoints, plus AI-discovered per-domain /fetch endpoints, residential/ISP/mobile proxy routing via proxy.spider.cloud, CDP/WebDriver BiDi cloud browsers, scraper directory lookups, crawl logs, and a credits endpoint. All endpoints accept and return JSON (also XML, CSV, JSONL via content-type) and authenticate with Bearer API keys. Up to 10,000 RPM per account.

- **Human URL:** [https://spider.cloud/docs/api](https://spider.cloud/docs/api)
- **Base URL:** `https://api.spider.cloud`

#### Tags

- Crawling
- Scraping
- Data Extraction
- URLs
- AI
- Markdown
- Search
- Screenshot
- Headless Browser
- Proxies

#### Properties

- [Documentation](https://spider.cloud/docs/api)
- [Documentation](https://spider.cloud/docs/overview)
- [OpenAPI](openapi/spider-cloud-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/spider-cloud.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spider-cloud.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://spider.cloud/docs/api)
- [Rate Limits](https://spider.cloud/docs/api)

### Spider Cloud MCP Server

Spider's hosted Model Context Protocol server exposes 22 tools — eight core operations (crawl, scrape, search, links, screenshot, unblocker, transform, get_credits), five AI-routed variants, and nine browser-automation tools (open, navigate, click, fill, screenshot, content, evaluate, wait_for, close) — to any MCP-compatible client. Authenticated with a Bearer API key. Also runnable locally via `npx spider-cloud-mcp`.

- **Human URL:** [https://spider.cloud/docs/integrations/mcp](https://spider.cloud/docs/integrations/mcp)
- **Base URL:** `https://mcp.spider.cloud/mcp`

#### Tags

- MCP
- AI
- Agents
- Crawling
- Scraping
- Browser Automation

#### Properties

- [Documentation](https://spider.cloud/docs/integrations/mcp)
- [Source Code](https://github.com/spider-rs/spider-cloud-mcp-v2)
- [Authentication](https://spider.cloud/docs/integrations/mcp)
- [Postman Collection](collections/spider-cloud.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spider-cloud.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://spider.cloud)
- [Documentation](https://spider.cloud/docs/overview)
- [API Reference](https://spider.cloud/docs/api)
- [Guides](https://spider.cloud/guides)
- [Pricing](https://spider.cloud/pricing)
- [Status Page](https://spidercloud.statuspage.io)
- [GitHub Organization](https://github.com/spider-rs)
- [Source Code](https://github.com/spider-rs/spider)
- [S D Ks](https://github.com/spider-rs/spider-clients)
- [SDK](https://github.com/spider-rs/spider-py)
- [SDK](https://github.com/spider-rs/spider-nodejs)
- [SDK](https://docs.rs/spider)
- [M C P](https://mcp.spider.cloud/mcp)
- [Integrations](https://spider.cloud/docs/integrations/mcp)
- [Integration](https://spider.cloud/docs/integrations/langchain)
- [Integration](https://spider.cloud/docs/integrations/llamaindex)
- [Integration](https://spider.cloud/docs/integrations/crewai)
- [Integration](https://spider.cloud/docs/integrations/flowiseai)
- [Integration](https://spider.cloud/docs/integrations/agno)
- [Integration](https://spider.cloud/docs/integrations/zapier)
- [Integration](https://spider.cloud/docs/integrations/x402)
- [Support](mailto:support@spider.cloud)
- [Plans](plans/spider-cloud-plans-pricing.yml)
- [Rate Limits](rate-limits/spider-cloud-rate-limits.yml)
- [Fin Ops](finops/spider-cloud-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
