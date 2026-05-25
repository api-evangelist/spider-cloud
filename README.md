# Spider (spider-cloud)

Spider is a Rust-based, AI-friendly web scraping and crawling cloud. Point it at a URL and get back clean markdown, structured JSON, screenshots, or links — at up to 100K pages per second — with anti-bot bypass, residential proxies, headless browsers, and native MCP, LangChain, LlamaIndex, CrewAI, and AutoGen integrations.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/spider-cloud/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

 - Crawling, Scraping, Data Extraction, URLs, AI, Markdown, MCP, Rust, Headless Browser, Proxies

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### Spider API

The Spider Cloud REST API exposes core `/crawl`, `/scrape`, `/search`, `/links`, `/screenshot`, `/unblocker`, and `/transform` endpoints, plus AI-discovered per-domain `/fetch` endpoints, residential/ISP/mobile proxy routing via `proxy.spider.cloud`, CDP/WebDriver BiDi cloud browsers, scraper directory lookups, crawl logs, and a credits endpoint. All endpoints accept and return JSON (also XML, CSV, JSONL via content-type) and authenticate with Bearer API keys. Up to 10,000 RPM per account.

**Human URL:** [https://spider.cloud/docs/api](https://spider.cloud/docs/api)

**Base URL:** `https://api.spider.cloud`

#### Tags

 - Crawling, Scraping, Data Extraction, URLs, AI, Markdown, Search, Screenshot, Headless Browser, Proxies

#### Properties

- [Documentation](https://spider.cloud/docs/api)
- [Documentation](https://spider.cloud/docs/overview)
- [OpenAPI](openapi/spider-cloud-openapi.yml)
- [Authentication](https://spider.cloud/docs/api)
- [RateLimits](https://spider.cloud/docs/api)
- [NaftikoCapability — Crawling](capabilities/spider-cloud-crawling.yaml)
- [NaftikoCapability — Scraping](capabilities/spider-cloud-scraping.yaml)
- [NaftikoCapability — Search and Links](capabilities/spider-cloud-search.yaml)
- [NaftikoCapability — Browser and Screenshot](capabilities/spider-cloud-browser.yaml)
- [NaftikoCapability — Account Data](capabilities/spider-cloud-data.yaml)

### Spider Cloud MCP Server

Spider's hosted Model Context Protocol server exposes 22 tools — eight core operations (crawl, scrape, search, links, screenshot, unblocker, transform, get_credits), five AI-routed variants, and nine browser-automation tools — to any MCP-compatible client. Authenticated with a Bearer API key. Also runnable locally via `npx spider-cloud-mcp`.

**Human URL:** [https://spider.cloud/docs/integrations/mcp](https://spider.cloud/docs/integrations/mcp)

**Base URL:** `https://mcp.spider.cloud/mcp`

#### Tags

 - MCP, AI, Agents, Crawling, Scraping, Browser Automation

#### Properties

- [Documentation](https://spider.cloud/docs/integrations/mcp)
- [SourceCode](https://github.com/spider-rs/spider-cloud-mcp-v2)
- [Authentication](https://spider.cloud/docs/integrations/mcp)

## Common Properties

- [Website](https://spider.cloud)
- [Documentation](https://spider.cloud/docs/overview)
- [API Reference](https://spider.cloud/docs/api)
- [Guides](https://spider.cloud/guides)
- [Pricing](https://spider.cloud/pricing)
- [Status](https://spidercloud.statuspage.io)
- [GitHub Organization](https://github.com/spider-rs)
- [Source — Spider Core (Rust)](https://github.com/spider-rs/spider)
- [SDKs (clients)](https://github.com/spider-rs/spider-clients)
- [SDK — Python](https://github.com/spider-rs/spider-py)
- [SDK — Node.js](https://github.com/spider-rs/spider-nodejs)
- [SDK — Rust](https://docs.rs/spider)
- [MCP Endpoint](https://mcp.spider.cloud/mcp)
- [Integration — MCP](https://spider.cloud/docs/integrations/mcp)
- [Integration — LangChain](https://spider.cloud/docs/integrations/langchain)
- [Integration — LlamaIndex](https://spider.cloud/docs/integrations/llamaindex)
- [Integration — CrewAI](https://spider.cloud/docs/integrations/crewai)
- [Integration — FlowiseAI](https://spider.cloud/docs/integrations/flowiseai)
- [Integration — Agno](https://spider.cloud/docs/integrations/agno)
- [Integration — Zapier](https://spider.cloud/docs/integrations/zapier)
- [Integration — x402](https://spider.cloud/docs/integrations/x402)
- [Support](mailto:support@spider.cloud)
- [Plans](plans/spider-cloud-plans-pricing.yml)
- [Rate Limits](rate-limits/spider-cloud-rate-limits.yml)
- [FinOps](finops/spider-cloud-finops.yml)

## Generated Artifacts

- `openapi/` — OpenAPI 3.0.3 specification covering the documented Spider Cloud REST endpoints (`/crawl`, `/scrape`, `/search`, `/links`, `/screenshot`, `/unblocker`, `/transform`, `/fetch/{domain}/{path}`, `/data/scraper-directory`, `/data/crawl_logs`, `/data/credits`).
- `capabilities/` — Five Naftiko capability files grouping the API surface into Crawling, Scraping, Search and Links, Browser and Screenshot, and Account Data. Each capability exposes both REST and MCP adapters.
- `plans/` — API Commons Plans 0.1 file mapping Spider's pay-as-you-go credit model: $1/GB bandwidth + $0.001/compute-minute, with free sign-up credits, an AI-routing subscription tier, and enterprise custom pricing.
- `rate-limits/` — API Commons Rate Limits 0.1 file documenting the default 10,000 RPM per-account limit, browser session concurrency (5) and idle timeout (5 min), and enterprise-negotiated overrides.
- `finops/` — FOCUS 1.3 / FinOps Framework mapping with bandwidth, compute, successful-request, and credit-balance meters plus unit-economics targets (cost per GB, cost per compute minute, cost per 1K successful requests).

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
