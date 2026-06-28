# Contributor Guide

## Purpose

This wiki is **community-maintained** by the [r/AWSCertifications](https://reddit.com/r/AWSCertifications) community. Anyone can contribute — whether you're fixing a typo, adding a new resource, or updating an exam guide.

## Ways to Contribute

- Fix typos and formatting issues
- Update exam versions and exam codes
- Add new certification resources and study materials
- Update vouchers, discounts, and promotions
- Improve study guides with better content
- Add hands-on project ideas
- Report outdated or incorrect information

## Repository Structure

```
docs/
├── index.md                  # Homepage
├── contributor-guide.md      # This page
├── certification-pathways.md # Expanded certification roadmaps (20+ pathways)
├── aws-cloud-institute.md    # AWS Cloud Institute program guide
├── aws-community-builder.md  # AWS Community Builder program guide
├── programs-similar-skills-to-jobs.md # AWS programs & initiatives
├── vouchers-discounts.md     # Vouchers & promotions
├── exam-benefits.md          # Exam pass benefit FAQ
├── exam-results.md           # Results timeline FAQ
├── free-learning.md          # Free learning resources
├── digital-badges.md         # AWS Knowledge Badges
├── microcredentials.md       # AWS microcredentials
├── projects-hands-on.md      # Hands-on practice
├── practice-exam-scores.md   # Score interpretation
├── etc-rewards.md            # ETC program FAQ
├── tutorialsdojo.md          # TD vs Udemy comparison
├── subreddit-rules.md        # Community rules
├── foundational/             # Foundational-level guides
│   ├── cloud-practitioner.md
│   └── ai-practitioner.md
├── associate/                # Associate-level guides
│   ├── solutions-architect.md
│   ├── developer.md
│   ├── data-engineer.md
│   ├── machine-learning.md
│   └── cloudops.md
├── professional/             # Professional-level guides
│   ├── solutions-architect-pro.md
│   ├── devops-engineer-pro.md
│   └── genai-developer-pro.md
└── specialty/                # Specialty-level guides
    ├── security.md
    └── advanced-networking.md
```

The navigation structure is defined in `mkdocs.yml` at the repository root.

## Getting Started

### Prerequisites

- [Python](https://www.python.org/downloads/) 3.8 or later
- [Git](https://git-scm.com/)

### Local Development

1. Fork and clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/AWSCertificationsWiki.git
cd AWSCertificationsWiki
```

2. Install MkDocs and the Material theme:

```bash
pip install mkdocs-material
```

3. Start the local dev server:

```bash
mkdocs serve
```

This starts a live-reloading server at `http://127.0.0.1:8000` — changes you make to markdown files will appear automatically.

4. Build the static site:

```bash
mkdocs build --strict
```

The `--strict` flag treats warnings as errors, ensuring a clean build. Output goes to the `site/` directory.

### Making Changes

1. Edit the relevant markdown file under `docs/`
2. Run `mkdocs serve` to preview your changes
3. Run `mkdocs build --strict` to verify the build
4. Commit and push to your fork
5. Open a pull request

## Style Guide

- Use Material theme admonitions: `!!! tip`, `!!! warning`, `!!! note`, `!!! info`, `!!! danger`
- Use `[]()` markdown links with descriptive text — never raw URLs
- Prefer internal wiki links (e.g. `[Vouchers](vouchers-discounts.md)`) over external Reddit links when a wiki page exists
- Keep pages focused and avoid duplicating content from other pages
- Add a "Related Pages" section at the bottom of major guide pages
- Use consistent heading hierarchy: `##`, then `###`, then `####`

## Before Submitting

- Verify the site builds with `mkdocs build --strict`
- Check that all internal links resolve correctly
- Ensure no broken admonitions (use `!!!` not `> [!`)
- Review for consistent formatting with existing pages

## Need Help?

- Open an [issue](https://github.com/AWSCertifications/AWSCertificationsWiki/issues) on GitHub
- Post on [r/AWSCertifications](https://reddit.com/r/AWSCertifications)

## See Also

- [CONTRIBUTING.md](https://github.com/AWSCertifications/AWSCertificationsWiki/blob/main/CONTRIBUTING.md) — quick reference on GitHub
- [Community Rules](subreddit-rules.md) — code of conduct for contributors
