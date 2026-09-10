# maps.alexpriest.com

Hand-built city guides, one self-contained HTML file per city, that work with no network at all.

## Status

Shipped — one guide so far, Mexico City, verified July 2026.

## License

Not licensed for reuse.

- Each guide is a **single self-contained HTML file** — basemap baked in as a data URI, no external requests, works offline.
- `noindex, nofollow`. Unlisted, not secret.
- Deploy: `vercel --prod`. DNS is a **DNS-only** (grey-cloud) CNAME in Cloudflare, matching `clients.alexpriest.com`.

## Guides
- `/cdmx/` — Mexico City. Built from Swarm check-ins across two trips, verified July 2026.
