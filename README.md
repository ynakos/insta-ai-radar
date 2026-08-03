# Insta AI Radar

Instagram saved-collections AI radar. Auto-generated reports produced by the **YN-INSTA-CHANNELS** Claude Code skill: it reads the owner's Instagram saved collections (via OpenCLI browser automation on the owner's own logged-in Chrome session), analyzes each saved publication (caption + local audio transcription when needed), and publishes card-based reports here. Reports live in `docs/` and are served via GitHub Pages.

## Report structure

Each report is a set of cards, one per saved publication. Every card contains:

- **Saved folder name** — the Instagram saved collection the publication belongs to
- **Publication date**
- **3-sentence synopsis** of the publication's content
- **Keywords** — including technology and product names mentioned
- **Link to the publication**
- **Link to the author's account**
- **Following indicator** — ✅ if the owner follows the author, ❌ otherwise

## Notes

- Content covered here is the owner's own saved bookmarks on Instagram.
- Reports are generated on the owner's machine; this repository only hosts the published output.
- Reports are published under `docs/reports/` and served via GitHub Pages from the `docs/` folder.
