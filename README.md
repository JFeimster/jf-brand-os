# jf-brand-os

Source-of-truth repo for Jason Feimster’s personal brand system: bios, resume assets, media kit, prompts, website starter files, and documentation.

## Purpose
This repository acts as the operating system for Jason Feimster’s personal brand across web, social, media, speaking, author pages, and future AI-assisted workflows.

## Core areas
- `docs/` — source-of-truth brand, bio, resume, media, reference, and site-support documentation
- `prompts/` — reusable prompts for generating and updating brand assets
- `site/` — static starter website files and docs-style navigation pages
- `assets/` — shared images and global front-end styling assets
- `archive/` — deprecated drafts and old variants once there is enough history to justify them

## Current architecture
The live repo is organized around the current working structure rather than the older numbered-folder schema. Prefer adding new files into the active architecture:
- `docs/admin/`
- `docs/brand-bio/`
- `docs/credentials/`
- `docs/resume/`
- `docs/media-kit/`
- `docs/brands/`
- `docs/reference/`
- `docs/site-assets/`
- `docs/content-assets/`
- `prompts/`
- `site/`

## Current goals
1. Maintain a clean source of truth for bios, resume materials, and brand infrastructure
2. Publish a docs-style personal brand site that is Vercel-friendly and scalable
3. Store reusable prompts and supporting documentation in one place
4. Build a maintainable roadmap for the next waves of files, pages, and assets

## Roadmap and backlog
Primary backlog source:
- `TODO.md`

Tracking issues:
- [#1 Roadmap: prioritized create-next backlog tracker](https://github.com/JFeimster/jf-brand-os/issues/1)
- [#2 Tier 1: foundation and admin docs backlog](https://github.com/JFeimster/jf-brand-os/issues/2)
- [#3 Tier 1: brand, bio, and credentials docs backlog](https://github.com/JFeimster/jf-brand-os/issues/3)
- [#4 Tier 1: resume, media, brands, prompts, site-assets, and reference docs backlog](https://github.com/JFeimster/jf-brand-os/issues/4)
- [#5 Tier 2: useful backlog for depth and expansion](https://github.com/JFeimster/jf-brand-os/issues/5)
- [#6 Tier 3: optional and deferred backlog](https://github.com/JFeimster/jf-brand-os/issues/6)

## Recommended next sprint
A strong next batch to create:
- `PROJECT_OVERVIEW.md`
- `CHANGELOG.md`
- `docs/admin/project-scope.md`
- `docs/admin/content-inventory.md`
- `docs/brand-bio/messaging-pillars.md`
- `docs/brand-bio/brand-vocabulary.md`
- `docs/brand-bio/anti-patterns-and-things-to-avoid.md`
- `docs/brand-bio/about-jason-feimster-medium.md`
- `docs/brand-bio/about-jason-feimster-short.md`
- `docs/credentials/military-background-and-context.md`
- `docs/credentials/founder-operator-experience.md`
- `docs/resume/role-targeting-framework.md`

## GitHub Projects suggestion
For visual progress tracking, set up a GitHub Project with these views:
- **Board view** with columns: `Backlog`, `Ready`, `In Progress`, `Review`, `Done`
- **Table view** with fields such as: `Tier`, `Area`, `Type`, `Status`, `Priority`, `Owner`
- **Roadmap view** if you want to group by sprint or milestone later

Recommended custom fields:
- `Tier` → Tier 1 / Tier 2 / Tier 3
- `Area` → Admin / Brand Bio / Credentials / Resume / Media Kit / Brands / Prompts / Site Assets / Reference / Content Assets / Archive
- `Type` → Doc / Prompt / Site Page / Refactor / Archive
- `Priority` → High / Medium / Low

Recommended workflow:
1. Add issues #2 through #6 to the Project
2. Group by `Status` for day-to-day tracking
3. Slice by `Tier` for strategic planning
4. Add future file-creation issues to the same Project rather than scattering them

## Notes
- Prefer updating canonical source docs before derivative assets
- Avoid duplicating files when an existing source-of-truth file can be expanded
- Do not revive the old numbered-folder structure unless there is a compelling migration reason
- Keep the docs/site relationship clean so the repo stays useful for both humans and AI-assisted workflows
