# Spider (spider-cloud)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
