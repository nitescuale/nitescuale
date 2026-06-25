# Alexandru Nitescu

Freshly Graduated Data Science & Applied Mathematics engineer, currently a Data Analyst / Data Engineer apprentice at Exponens in Paris. Relocating to Singapore / East Asia from October 2026 — open to Data Scientist, AI, and ML Engineer roles requiring visa or Employment Pass sponsorship.

I build production-grade projects end to end — from data pipeline to deployed product — rather than isolated notebooks. The two repos below are the most representative examples.

---

## Projects

### [ALICE](https://github.com/nitescuale/alice)
Local-first, cross-platform desktop RAG assistant.
- **Stack:** Tauri 2, React/TypeScript, Python/FastAPI, ChromaDB, sentence-transformers, Ollama
- Fully local LLM inference — no document or query ever leaves the device
- GPU-accelerated transcription (faster-whisper) for podcast/audio ingestion

### [Job Applier](https://github.com/nitescuale/job-apply-agent)
Chrome/Firefox extension + FastAPI backend orchestrating a multi-agent job application pipeline.
- **Stack:** React, TypeScript, Vite/CRXJS, MV3 service worker, FastAPI, Google Gemini, pdfminer.six, SQLite
- Cascading job scraper (JSON-LD JobPosting → Open Graph → text fallback) refined by Gemini
- Deterministic offer/profile match scorer with LLM cascade
- Section-aware DOCX-in-place CV tailoring → PDF (docx2pdf / LibreOffice)
- Bilingual long-form cover letter generation
- Deterministic ATS lint via pdfminer.six
- React-safe DOM form auto-fill
- SQLite-backed application tracking with a full-page dashboard
- 41 pytest-covered tests

### [Fablify](https://fablify.app)
Deployed full-stack SaaS generating multilingual children's stories via the Claude API.
- **Stack:** Claude API, Next.js, Supabase (Postgres, RLS), Stripe, Vercel
- Stripe subscription billing — Checkout, Customer Portal, signed webhooks
- Backend-enforced credit limits; RLS-secured database

---

## Background

- **Exponens (Paris)** — Led the adoption of AI agentic coding (Claude Code) across the dev team: pitched leadership through a code audit demo, then handled training and internal AI governance. Built and automated data pipelines processing 100M+ records daily; designed BI dashboards used by 5+ business teams.
- **Renault Group (Bucharest)** — Prototyped an LLM-based Data Quality framework as a proof-of-concept, fine-tuning small open-source models (Llama, Qwen) with prompt engineering.
- **Dataiku certified** — Core Designer, Advanced Designer, ML Practitioner, MLOps Practitioner.

## Contact

[LinkedIn](https://www.linkedin.com/in/nitescuale/)
