<!-- README.md -->
# Phaze‑Hugging

Terminal‑style AI web platform using Hugging Face models.

## Features
- Prompt-driven UI (React + Tailwind)
- REST + GraphQL endpoints (Node/Express with SHA‑256 cache)
- CI/CD via GitHub Actions
- No paid dependencies
- Prompt presets support

## Quickstart
```bash
git clone https://github.com/professor‑tucker/phaze‑hugging.git
cd phaze‑hugging
npm install
cd frontend && npm install && npm run dev
cd backend && npm install && npm run build && node dist/index.js
