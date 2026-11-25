# Ikhsan Tahir

**AI Engineer & AI-Native Product Builder** · Jakarta, Indonesia  
Applied Computer Vision (`PyTorch` / `YOLO11` / `ONNX`) · Full-Stack & Desktop Delivery (`Python` / `FastAPI` / `TypeScript` / `React` / `Tauri`) · Multi-Agent Coding Workflows (`Claude Code`, `Codex`, `Cursor`)

[Portfolio (`icxhnk.com`)](https://icxhnk.com) · [LinkedIn](https://www.linkedin.com/in/miftahulikhsan/) · [Email](mailto:icxhnk@gmail.com)

---

### About

I combine hands-on deep learning and full-stack product engineering with **2+ years of industrial Quality Control experience** (Shipyard QC In-Charge across 15 newbuilding vessels) and a **B.Eng. in Marine Engineering** (Hasanuddin University — CNN ship plate corrosion detection thesis).

That background shapes how I ship software with AI coding agents: **spec-first PRDs, objective ML evaluation gates, automated Playwright/Pytest verification, and fail-closed production deployments** rather than untested demos.

---

### Featured Open-Source Project

#### [SnapQC — Maritime Welding AI Visual Inspection](https://github.com/icxhnk/snapqc) · [Live App](https://snapqc.icxhnk.com)
- Trained a custom **YOLO11n** welding defect detector on RTX 5060 (2,028 CC0 images, 5,686 bounding boxes), reaching **80.2% Bad Weld AP@50**, **71.5% Good Weld AP@50**, and **59.7% held-out test mAP@50** (`64.8%` val).
- Applied a **Champion/Challenger MLOps gate** (`YOLO11n@640px` vs `YOLO11s@960px`) to ship a lightweight **10.13 MB ONNX** model running at **~32 ms CPU inference**.
- Built **SAHI 2×2 overlapping tiled inference** for high-resolution phone photos, **Human-in-the-Loop** inspector verification, **SQLite Active Learning** YOLO label export, formal A4 PDF reporting, Docker containerization, and OAuth 2.0 PKCE authentication.

---

### Shipped Production Products & Prototypes

| Product | Status | What It Does | Core Stack |
| :--- | :---: | :--- | :--- |
| **[SnapQC](https://snapqc.icxhnk.com)** ([Repo](https://github.com/icxhnk/snapqc)) | Live | Camera-assisted maritime welding visual inspection & QC reporting | Python, PyTorch, YOLO11n, ONNX Runtime, SAHI, SQLite, Docker |
| **[Klipros](https://klipros.sbs)** | Live | Native Windows AI video-clipping desktop app with GPU smart framing, ASR subtitles & multi-stream live support | Tauri, Rust, React, TypeScript, Python, CUDA, OpenCV |
| **[Central Identity & SSO](https://accounts.icxhnk.com)** | Live | Shared OAuth 2.0 Authorization Code + PKCE S256 / RS256 JWKS auth, session & RBAC backend across live products | Python, FastAPI, PostgreSQL, SQLAlchemy, Alembic |
| **[Tonroang](https://tonroang.site)** | Live | Multi-tenant venue/SME booking & operations web app (Midtrans/Mayar QRIS, idempotency & concurrency guards) + customer mobile app | Node.js, PostgreSQL, SQLite, React Native (Expo) |
| **[Erasion](https://erasion.site)** | Live | Privacy-first Chrome Extension & local utility for managing user-owned X posts/reposts without external token storage | Chrome Extension (MV3), Python, Playwright, Pytest |
| **[GuruExcel](https://guruexcel.icxhnk.com)** | Live | Interactive Indonesian spreadsheet learning platform (44 modules, progress tracking & printable PDF summaries) | Web Frontend, JavaScript, Interactive Grid Engine |
| **DockLedger** | Prototype | Maritime hull/repair inspection & repair-control workspace with HEIC/PDF evidence and drawing-revision tracking | Node.js, Sharp, PDFKit, HEIC/PDF Pipeline |

*(Commercial product repositories are kept private; live demos above are publicly accessible and private contributions are enabled on my contribution graph.)*

---

### Core Stack

- **AI Agents & Engineering Workflow:** Claude Code, OpenAI Codex, Cursor, Antigravity, MCP integrations, spec-first PRD-to-MVP delivery, prompt & eval engineering
- **Applied AI & Computer Vision:** PyTorch (CUDA), YOLO11, ONNX Runtime, SAHI tiled inference, OpenCV, CNN image processing, Human-in-the-Loop & Active Learning
- **Full-Stack, Desktop & Mobile:** Python, FastAPI, TypeScript, React, Next.js, Node.js, Express, Vite, TailwindCSS, Tauri (Rust), React Native (Expo), Chrome Extensions (MV3)
- **Data, Auth & DevOps:** PostgreSQL, SQLite, SQLAlchemy, Alembic, OAuth 2.0 + PKCE (RS256/JWKS), Docker, Coolify, Cloudflare, Playwright, Pytest, Git
