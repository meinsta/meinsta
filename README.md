# Meina Ghafouri

**Product marketer at [Qdrant](https://qdrant.tech)**

Product marketing for AI infrastructure, vector search, and developer platforms.  
Previously: Teleport, Okta, Auth0. Built on a career in engineering.

## Links
- Website: [meina.me](https://meina.me)
- LinkedIn: [linkedin.com/in/meina-ghafouri](https://www.linkedin.com/in/meina-ghafouri)
- Writing: [Filtered Vector Search: What ACORN Fixes, and What Fixes ACORN](https://qdrant.tech/articles/filtered-vector-search-acorn/) (Qdrant)
- Author hub: [Teleport publications](https://goteleport.com/learn/author/meina-ghafouri/)

## Field kits

Go-to-market systems as kits you can run: one made-up company, one cluster, a frozen set of golden
questions, and a measured result in every README. Each kit matches a system on [meina.me](https://meina.me).

| Kit | What it does |
|---|---|
| [`field-kit`](https://github.com/meinsta/field-kit) | The shared core: single-file building blocks for systems that put Qdrant behind an agent. |
| [`grounding-layer`](https://github.com/meinsta/grounding-layer) | A scheduled refresh that keeps product and field sources current in Qdrant, ending in a recall gate. |
| [`org-knowledge-mcp`](https://github.com/meinsta/org-knowledge-mcp) | An MCP server that answers from your own sources and checks that every claim is cited. |
| [`field-systems`](https://github.com/meinsta/field-systems) | Field cards built from those sources, with a weekly check that proposes a fix when a source changes. |
| [`field-guides`](https://github.com/meinsta/field-guides) | Deal-backed guide outlines that keep what ships today apart from what is still open, with expert review. |
| [`page-engine`](https://github.com/meinsta/page-engine) | Product pages and paid landings where every detail is a docs sentence and authored words are judged in code. |

## Qdrant Edge demos

Qdrant's DevRel team built the four demo applications on [qdrant.tech/edge](https://qdrant.tech/edge/).
I wrote the Demos section of that page and got three of the applications running as public demos
anyone can open in a browser.

| Demo | Live | What I did |
|---|---|---|
| Sentinel | [sentinel-edge-demo.vercel.app](https://sentinel-edge-demo.vercel.app/) | Made the frontend deployable without its local data folder, moved the clips to hosted storage, and rebuilt the search collection. Fix proposed upstream in [video-anomaly-edge#21](https://github.com/qdrant/video-anomaly-edge/pull/21). |
| Edge Visual Search | [edge-visual-search.vercel.app](https://edge-visual-search.vercel.app/) | Fixed a search error and made the video source configurable, then hosted the API. Fix proposed upstream in [devrel-projects#1](https://github.com/qdrant-labs/devrel-projects/pull/1). |
| Smart Glasses | [smart-glasses-edge.vercel.app](https://smart-glasses-edge.vercel.app/) | Wrote a small API over the demo package so the browser demo can search, then hosted it. |

Page work: [landing_page#3113](https://github.com/qdrant/landing_page/pull/3113).

## More public work
- [`qdrant-oversampling-bench`](https://github.com/meinsta/qdrant-oversampling-bench): a benchmark I wrote that measures recall and p95 latency together across a binary-quantization oversampling sweep
- [`qdrant-opentelemetry-tutorial`](https://github.com/meinsta/qdrant-opentelemetry-tutorial): a sample showing Qdrant Cloud metrics in your own OpenTelemetry backend
