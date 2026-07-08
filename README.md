# AWSCertificationsWiki

Community-maintained knowledge base for [r/AWSCertifications](https://reddit.com/r/AWSCertifications).

Built with [MkDocs Material](https://squidfunk.github.io/mkdocs-material/).

## Quick Start

```bash
pip install mkdocs-material
mkdocs serve     # preview at http://127.0.0.1:8000
mkdocs build --strict  # production build
```

## Project Structure

```
docs/
├── index.md                  # Homepage
├── 404.md                    # Custom 404 page
├── faq.md                    # FAQ landing page
├── certification-pathways.md # 20+ career pathways
├── microcredentials.md       # AWS Learning Programs & Badges
├── ...                       # 15+ additional FAQ and resource pages
├── foundational/             # Cloud Practitioner, AI Practitioner
├── associate/                # SAA, DVA, DEA, MLA, CloudOps
├── professional/             # SAP, DOP, GenAI Developer Pro
└── specialty/                # Security, Advanced Networking

overrides/
├── main.html                 # Open Graph / Twitter meta tags
└── partials/
    └── announce.html         # Announcement banner

docs/assets/
├── images/
│   ├── certifications/       # Certification badge images (12)
│   └── social-preview.svg    # Social sharing preview
└── stylesheets/
    └── extra.css             # Custom styles, badges, accessibility
```

## Standard Certification Page Structure

1. Header with badge and level indicator
2. Quick Facts table
3. tl;dr summary
4. Who Should Take (foundational only)
5. Exam Details with domains
6. Video Courses (Free then Paid)
7. Additional Resources / Additional Material
8. Practice Exams (Free then Paid)
9. Books (if applicable)
10. Hands-on Resources
11. Community Advice
12. Exam Tips
13. FAQ
14. Related Pages

## Contributing

See [Contributor Guide](docs/contributor-guide.md) and [CONTRIBUTING.md](CONTRIBUTING.md).
