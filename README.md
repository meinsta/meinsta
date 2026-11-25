# Meina Ghafouri

**Product marketer at [Qdrant](https://qdrant.tech)**

I build go-to-market systems for AI infrastructure and vector search, and I came to product
marketing from engineering. Before Qdrant I worked at Teleport, Okta and Auth0. I like to hand a
team a system it can run, so most of the work below comes with code.

## Links
- Website: [meina.me](https://meina.me)
- LinkedIn: [linkedin.com/in/meina-ghafouri](https://www.linkedin.com/in/meina-ghafouri)
- Writing: [Filtered Vector Search: What ACORN Fixes, and What Fixes ACORN](https://qdrant.tech/articles/filtered-vector-search-acorn/) (Qdrant)
- Author hub: [Teleport publications](https://goteleport.com/learn/author/meina-ghafouri/)

## Field Kits

Go-to-market systems you can run on a made-up company, each with a measured result in its README.

**Start at [`field-kit`](https://github.com/meinsta/field-kit).** It explains the path, runs every
kit from a script, and holds the code they share. Each kit matches a system on
[meina.me](https://meina.me), and this table lists them in the order they run.

| Kit | What It Does |
|---|---|
| 1. [`grounding-layer`](https://github.com/meinsta/grounding-layer) | Keeps product and field sources current in Qdrant on a schedule, ending in a recall gate |
| 2. [`org-knowledge-mcp`](https://github.com/meinsta/org-knowledge-mcp) | Answers from your own sources through an MCP server that checks each claim against the line it cites |
| 3. [`field-systems`](https://github.com/meinsta/field-systems) | Builds field cards from those sources and proposes a fix each week a source changes |
| 4. [`field-guides`](https://github.com/meinsta/field-guides) | Outlines deal-backed guides with shipped facts and open questions kept apart, plus expert review |
| 5. [`page-engine`](https://github.com/meinsta/page-engine) | Builds product pages and paid landings where the docs supply every detail and code judges the words you write |

## Public Work
- [Qdrant website](https://qdrant.tech): 26 merged pull requests since July 2026. I built the GPU Indexing page, rebuilt the Cloud Inference page, shipped 13 paid search landing pages, added click and scroll-depth tracking to the Cloud and product pages, and fixed navigation, page metadata and structured data across the site. On the [Edge page](https://qdrant.tech/edge/) I wrote the Demos section.
- [Sentinel](https://sentinel-edge-demo.vercel.app/): a Qdrant Edge demo built by Qdrant's DevRel team. I made its frontend deployable from hosted data, moved the clips to hosted storage, and rebuilt the search collection.
- [Edge Visual Search](https://edge-visual-search.vercel.app/): a Qdrant Edge demo built by DevRel. I fixed a search error, made the video source configurable, and hosted the API.
- [Smart Glasses](https://smart-glasses-edge.vercel.app/): a Qdrant Edge demo built by DevRel. I wrote a small API over the demo package so the browser demo can search, and hosted it.
- [`qdrant-oversampling-bench`](https://github.com/meinsta/qdrant-oversampling-bench): a benchmark I wrote that measures recall and p95 latency together across an oversampling sweep with binary quantization.
- [`qdrant-opentelemetry-tutorial`](https://github.com/meinsta/qdrant-opentelemetry-tutorial): a sample that shows Qdrant Cloud metrics in your own OpenTelemetry backend.
