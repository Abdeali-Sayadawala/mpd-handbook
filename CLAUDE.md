# CLAUDE.md: mpd-handbook

A public, friendly HTML guide for website users, NRI owners, partners and non-technical stakeholders: what My Property Doctors does, features, what admin / master franchise / franchise / provider / worker / customer can do, how onboarding works, plans, payments and the document vault.

## Repo-specific rules
- Plain language, no technical terms. Explain with screenshots and short steps.
- Describe only features that are live. Mark "coming soon" clearly.
- Pages: index, getting-started, document-vault, identity-verification, builders-and-societies, our-team (staff console), faq. Update them at the end of every milestone step.

## Rules that apply in every MPD repo
- Brand: **My Property Doctors (MPD)**. Read `BRAND_NAME`, `BRAND_SHORT` and `BRAND_DOMAIN` from config. Never hard-code the name or domain.
- TypeScript strict mode, ESLint + Prettier, Conventional Commits (`feat:`, `fix:`, `chore:`).
- Branches: `develop` → staging (auto deploy), `main` → production (manual deploy). Feature branches + merge requests.
- No secrets in git. Use `.env.example` with placeholders only. No real customer data in code, fixtures, logs or docs.
- No direct backend calls (static site). Describe the API only as documented in `mpd-backend/openapi.json`.
- Full spec: `../mpd-handbook-developer/docs/architecture/README.md`. Workspace notes: `../CLAUDE.md`. **Start of a session and the after-every-step checklist: `../mpd-context/README.md` and `08-workflow.md`.**

## Commands
```bash
open index.html in a browser
```
