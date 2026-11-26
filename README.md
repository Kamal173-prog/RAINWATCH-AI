# RAINWATCH AI

Integrated Heavy Rainfall Early Warning and Inundation Prediction for Odisha.

HACK-KALP 2026 entry — team Wanda_Maximoff (AI/ML, Senior). Finale: 26 November 2026, NIST.

## What's in this repo

- **`RAINWATCH-AI-Phase2-Google-Test-Fix.zip`** (67,182,006 bytes, 528 files) — the complete project: FastAPI backend (`rainfall-xgb-v3` production / `rainfall-xgb-v3.3` demo model), React frontend, NASA GPM IMERG satellite integration (Phases 0–2, live-verified twice on 2026-11-26), Google Weather integration with merged forecast (MODEL → GOOGLE WEATHER → UNAVAILABLE), frozen v3.3 model artifacts (15/15 SHA-256 verified), 245 backend tests, docs, and the 6-slide HackKalp deck.
- SHA-256: `dc337c5992bf481c63b626837132261fe9bf47b4775017b76ac18512d733aff8`

## Quick start

Unzip, then follow `RAINWATCH-AI/README.md` inside the archive (backend on :8001 with `MODEL_VERSION=rainfall-xgb-v3.3`, frontend on :5173). No `.env` or API keys ship in the package — see `backend/.env.example`.
