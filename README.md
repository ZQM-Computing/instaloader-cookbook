# Instaloader Cookbook

<!-- ZQM-START -->
<!-- markdownlint-disable MD033 -->
<p align="center">
  <strong>ZQM Computing — Geospatial Engineering & Scientific Computing</strong><br>
  <a href="https://github.com/ZQM-Computing">ZQM Computing</a>
</p>
<!-- markdownlint-enable MD033 -->
<!-- ZQM-END -->

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

A **Instaloader cookbook** — Instagram data collection from the command line. Second-tier OSINT tool in the wave-8 set. Patterns are planned from the design, not yet from fleet runs. Authenticated collection is session-gated; collect only public data you are allowed to collect. It is intended for Researchers who collect public Instagram posts and profiles for analysis. Validate each pattern against your own data, software versions, and operating environment before adopting it.

## Repository role and status

**Status:** Active, public — seeding. Pattern passes land in follow-up work from fleet-verified setups; the tables below list what is planned, not what is already written.

**What this repository is:** Instaloader patterns — see the table below.

**What it contributes:** Part of the ZQM Computing geospatial portfolio. The umbrella index for the series is [geospatial-cookbooks](https://github.com/ZQM-Computing/geospatial-cookbooks).

**Standing:** This repository is maintained independently. Automated checks cover only the paths and environments configured in its workflows; they do not establish production readiness or operational certification.

## Who this is for

Researchers who collect public Instagram posts and profiles for analysis.

## Prerequisites

- Instaloader in the fleet Python environment
- Python 3.11+
- A public profile or hashtag for the first pass

## Patterns (planned)

| # | Example | What it will demonstrate |
|---|---------|--------------------------|
| 01 | `01-first-download` | A first profile or hashtag download |
| 02 | `02-metadata` | Captions, timestamps, and media metadata |
| 03 | `03-session-notes` | Session handling for authenticated passes, without storing sessions in repos |

## Repository layout

```text
instaloader-cookbook/
├── examples/          # pattern passes, landing in follow-up work
├── README.md
└── LICENSE
```

## Roadmap

- First pattern pass: the first two table rows
- Second pass: the remaining rows, from fleet-verified setups

## Contributing

A contributing guide lands with the first pattern pass. Report security issues to <zqmcomputing@gmail.com> — please do not open a public issue for those.

## More from this series

- [snscrape-cookbook](https://github.com/ZQM-Computing/snscrape-cookbook) — Social media scraping from Python and CLI
- [blackbird-cookbook](https://github.com/ZQM-Computing/blackbird-cookbook) — Username search across social platforms
- [scrapy-cookbook](https://github.com/ZQM-Computing/scrapy-cookbook) — Polite web scraping spiders, pipelines, and exports
