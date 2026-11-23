# Content QA Playbook

Practical checklists and templates for verifying content and interfaces on a website and in a mobile app. Collected from real release checks: page publishing, reference data validation, responsive checks, DevTools, bug reports.

**Why:** content rarely breaks inside the editor. It breaks after publishing, in another browser, on another screen width, in an app with a stale cache. These checklists make checks repeatable and catch expensive mistakes: prices, promotion dates, tariff terms.

> The Russian version is the primary one: [README.md](README.md). This file is a short English overview.

## What is inside

| File | Purpose |
|---|---|
| [checklists/page-content.md](checklists/page-content.md) | Page checks before and after publishing |
| [checklists/cms-publishing.md](checklists/cms-publishing.md) | Publishing through a CMS: fields, media, preview, rollback |
| [checklists/reference-data.md](checklists/reference-data.md) | Price lists and catalogues: prices, terms, duplicates |
| [checklists/mobile-app.md](checklists/mobile-app.md) | Content checks in a mobile app |
| [checklists/devtools.md](checklists/devtools.md) | What to look at in browser DevTools |
| [templates/bug-report.md](templates/bug-report.md) | Bug report template |
| [templates/content-task.md](templates/content-task.md) | Content change request template |
| [templates/release-check.md](templates/release-check.md) | Content release checklist |
| [examples/bug-report-filled.md](examples/bug-report-filled.md) | Filled bug report example (in Russian) |
| [examples/content-task-filled.md](examples/content-task-filled.md) | Filled content task example (in Russian) |

## Principles

1. Compare with the source of truth, not with the previous version of the page: numbers, promotion dates, names, units.
2. Check after publishing, not only in the editor: cache, CDN, mobile app.
3. Keep evidence: screenshot, URL, app version, reproduction steps.
4. A wrong price or term is critical: report immediately.
5. After a fix, re-check the neighbouring pages that use the same template.

## License

MIT. Use and adapt freely. Templates are not tied to a specific CMS.
