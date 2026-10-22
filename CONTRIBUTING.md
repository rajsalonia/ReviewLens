# Contributing to ReviewLens

ReviewLens helps people compare **traceable evidence**, not opaque star ratings.

## Principles
- **Source transparency:** Every retrieved claim must retain source attribution and acquisition status.
- **No fabricated live signals:** Offline archive/demo results must never be represented as successful live API calls.
- **Authorized connectors only:** Use supported public or credentialed APIs, respect provider limits, and do not add bypass scraping.
- **Reproducibility:** Include deterministic test fixtures and clear steps for verifying new behavior.
- **Privacy:** Do not include credentials or personal data in pull requests.

## Local workflow
1. Follow [README.md](README.md) to configure the FastAPI backend and React/Vite frontend.
2. Use a feature branch and keep each PR to a single improvement.
3. Run `npm run build` and `npm run lint` for frontend changes.
4. Run the relevant backend tests documented in the README.
5. For new connectors, update [DATA_SOURCES.md](DATA_SOURCES.md) with required credentials, terms, reliability limits, and demo/live behavior.

## PR checklist
- [ ] Source and provenance behavior is correct
- [ ] Demo vs live status is explicitly tested
- [ ] No API keys, private data, or fabricated citations
- [ ] User-facing documentation reflects the change
