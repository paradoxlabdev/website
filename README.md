# Paradox Lab — Portfolio

Static single-page portfolio for [paradoxlab.dev](https://paradoxlab.dev) — resilient production systems across Web3 trading, AI automation, full-stack backends and B2B SaaS.

Paradox Lab is the work of a self-taught systems engineer focused on software that runs autonomously in production: Web3 / trading bots, business-process and AI automation, resilient API integrations, full-stack backends — and most recently a CRM platform with an MCP (Model Context Protocol) layer. This repository holds the source for the portfolio site itself.

## What's inside

The site is a single, self-contained `index.html` — inline CSS plus a small amount of vanilla JavaScript, with no build step and no external CSS/JS dependencies.

```
/
├── index.html        # Entire portfolio page (inline CSS + vanilla JS)
├── fonts/            # Self-hosted web fonts (Inter, JetBrains Mono — .woff2)
├── favicon.ico
├── sitemap.xml       # SEO sitemap
├── robots.txt        # Crawler directives
└── README.md
```

## Tech

- Static HTML5, CSS3 and vanilla JavaScript — all inlined in `index.html`
- Self-hosted fonts: Inter and JetBrains Mono (`.woff2`, via `@font-face`)
- Hosted on GitHub Pages
- SEO: `sitemap.xml`, `robots.txt`, Open Graph / Twitter Card meta, and JSON-LD structured data

No framework, bundler or package manager — the page renders as-is.

## Local preview

Everything is static, so any file server works. From the repo root:

```bash
python -m http.server 8000
```

Then open <http://localhost:8000>.

## Contact

- Web: [paradoxlab.dev](https://paradoxlab.dev)
- GitHub: [@paradoxlabdev](https://github.com/paradoxlabdev)
- X (Twitter): [@paradoxlabdev](https://x.com/paradoxlabdev)

## License

© 2026 Paradox Lab. All rights reserved.
