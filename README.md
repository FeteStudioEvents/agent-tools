# agent-tools — Fête Studio

Static tools and demos for Fête Studio's real-estate agent templates, served by GitHub Pages at
**https://fetestudioevents.github.io/agent-tools/**

| Path | What |
|---|---|
| `app/tour-day/` | Tour Day phone scoring app (installable, works after first open) |
| `tools/calendar/` | Deadline Desk “add all dates to your calendar” page |
| `demo/offer-night/` · `demo/deadline-desk/` · `demo/tour-day/` · `demo/listing-kit/` | Demos with sample data |

## How it deploys
`site.zip` holds the whole site. On every push to `main`, `.github/workflows/pages.yml` unzips it and deploys it
to GitHub Pages (Settings › Pages › Source = **GitHub Actions**). To update the site, replace `site.zip` and push.

Every link inside the site is relative, so the same files work at any address. Nothing a visitor types is uploaded:
Tour Day scores stay on the phone and travel only inside a share link; the calendar page reads dates from its own link.

## License — all rights reserved
© 2026 Fête Studio. All rights reserved. **Not open source.** This repository is public only so that GitHub Pages
can serve the tools to Fête Studio customers. No license is granted: you may use the hosted pages, but you may not
copy, modify, redistribute or resell the code, designs, text or images in this repository without written permission
from Fête Studio.
