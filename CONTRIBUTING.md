# Contributing to the r/AWSCertifications Wiki

Thank you for helping maintain the community knowledge base!

## How Community Members Can Suggest Changes

1. **Open an issue** on [GitHub](https://github.com/AWSCertifications/AWSCertificationsWiki/issues) describing the change
2. **Fork the repository**, make your changes, and submit a pull request
3. Use the **Edit button** on any wiki page (if enabled) to quickly submit edits

## How Moderators Can Update Pages

- All wiki pages live under the `docs/` directory as markdown files
- Navigation structure is defined in `mkdocs.yml`
- After making changes, run `mkdocs build --strict` to verify the site builds cleanly
- Push to `main` to trigger automatic deployment via GitHub Actions

## Style Guide

- Use Material theme admonitions (`!!! tip`, `!!! warning`, `!!! note`, `!!! info`, `!!! danger`)
- Use proper markdown links — never raw URLs
- Replace escaped markdown (`\#`, `\*`, `\*\*`) with proper formatting
- Prefer internal wiki links over Reddit cross-references when a wiki page exists
- Add "Related Pages" sections at the bottom of major pages
- Keep pages focused and avoid duplication

## Before Submitting

- Verify the site builds with `mkdocs build --strict`
- Check that all internal links resolve correctly
- Ensure no broken admonitions (use `!!!` not `> [!`)
- Review for consistent formatting with existing pages
