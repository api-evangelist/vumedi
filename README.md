# VuMedi

VuMedi (Vumedi, Inc.) operates a video education platform for physicians and other healthcare professionals. Founded in 2008 and headquartered in Oakland, California, with offices in Saint Louis Park, Minnesota and Zagreb, Croatia, it hosts long-form educational videos, webinars, conference coverage and case discussions from key opinion leaders and academic medical centers across 25+ clinical specialties, monetized through pharmaceutical and medical-device industry partnerships.

- Website: https://www.vumedi.com/
- Partners: https://www.vumedi.com/public/pages/partnering/
- GitHub: https://github.com/VuMedi
- Secondary-market profile: https://forgeglobal.com/vumedi_stock/

## API posture (probed 2026-08-02)

VuMedi publishes **no public API** — no developer portal, no API documentation, no OpenAPI/Swagger/GraphQL/AsyncAPI contract, no SDKs on any public registry, no MCP server and no A2A agent card. `api.vumedi.com`, `developer.vumedi.com` and `docs.vumedi.com` do not resolve. Every `/.well-known/` discovery path returns 404.

Its `robots.txt` explicitly Disallows every major AI/agent crawler (GPTBot, ClaudeBot, PerplexityBot, CCBot, Google-Extended, Applebot-Extended, Meta-ExternalAgent, Bytespider, Amazonbot, AI2Bot, Youbot) from the entire site — a deliberate closed posture toward automated and agentic consumption.

See `conformance/vumedi-conformance.yml` and `well-known/vumedi-well-known.yml` for the recorded evidence.
