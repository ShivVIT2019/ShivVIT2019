# Hi, I'm Sivasai Atchyut Akella 👋

**Backend-leaning full-stack ML engineer building deployed AI systems.**

MS CS (AI Concentration) @ Binghamton University, graduating **December 2026**.
Actively seeking full-time ML/AI Engineer roles (January 2027 start).

📧 sakella@binghamton.edu
🌐 [Portfolio](https://portfolio-nine-rho-36.vercel.app)
💼 [LinkedIn](https://linkedin.com/in/atchyut)

---

## What I Build

I build production AI systems — not just notebooks. Each project below is on GitHub with honest, measured metrics from saved artifacts, not reconstructed numbers.

**Stack:** Python · FastAPI · LangGraph · Gemini · Vertex AI · MCP · Google Cloud Run · Hugging Face Spaces · Docker · React · Streamlit · Gradio · ChromaDB · PostgreSQL · PyTorch · scikit-learn · ONNX · OpenCV · YOLOv5 · DistilBERT

---

## Featured Projects

### 💳 [CreditAI Global — Credit Approval System](https://github.com/ShivVIT2019/creditai-global) · [Live Demo](https://huggingface.co/spaces/sivasaiatchyut/creditai-global)
Dual-market credit risk platform for USA and India, live on Hugging Face Spaces.
- Random Forest trained on **100K rows** sampled from the Lending Club 2007–2018 dataset (~2.26M rows total on Kaggle) — **0.7042 ROC-AUC** on a 20K held-out test set (saved in `ml/artifacts/model_info.joblib`)
- Batch underwriting loop with Pydantic validation, five fraud rules, a priority-ordered policy engine, and a JSON Lines audit log
- India path maps CIBIL + city tier into the USA feature schema and calls the same model
- Three live Gradio tabs (scoring, pricing, batch underwriting); model artifacts shipped via Git LFS

### 🎯 [AI-Powered Campaign Targeting System](https://github.com/ShivVIT2019/Campaign_Targeting_System)
End-to-end ML system for ad campaign optimization.
- Random Forest on 12,330 UCI Online Shoppers sessions — **0.8932 ROC-AUC** (saved in `ml/train.ipynb`)
- Addressed **15.47%** class imbalance via precision-recall optimization
- FastAPI backend with **9 REST endpoints** + React KPI dashboard
- RAG-powered AI assistant using **Gemini + ChromaDB + Sentence Transformers**
- GitHub Actions CI/CD pipeline (backend tests + frontend build + Docker compose build with health check)

### 🤖 [FinSight AI — Multi-Agent Financial Intelligence](https://github.com/ShivVIT2019/finsight-ai)
LangGraph multi-agent system for real-time financial analysis.
- Research Agent + Risk Agent with shared TypedDict state, reasoning layer decoupled from tool execution
- Gemini 2.5 Flash function-calling loop, same tools exposed over MCP for external clients
- FastAPI backend + Streamlit dashboard, containerized with Docker

---

## Experience

**Uplifty** — AI Product Manager Intern & Team Lead *(Aug 2025 – Feb 2026)*
Built and deployed an NLP text-moderation system (DistilBERT, RNN, and rules engine) on Google Cloud Run, replacing paid third-party APIs with a self-hosted pipeline. Standardized ML deployment workflows across a 6-engineer team.

**Philips Innovation Campus** — R&D Intern *(Feb 2023 – Aug 2023)*
Named inventor on international patent application **PCT/EP2025/073715** ("Processing Ultrasound Image Data"), assigned to Koninklijke Philips N.V., filed August 2025. Architected laterality detection pipeline for obstetric ultrasound (apical / basal / subcostal classification) using YOLOv5, OpenCV, and ONNX on NVIDIA GPU servers.

**Binghamton University** — Research Assistant *(Jun 2025 – Dec 2025)*
Under Prof. Saumya Tripathi on "Exploring Global Perspectives in Social Work." Conducted 10 semi-structured interviews, analyzed qualitative data using Dedoose, contributed to literature reviews, and maintained IRB compliance via CITI Program certification.

---

## Patent

📄 **PCT/EP2025/073715** — "Processing Ultrasound Image Data"
Assignee: Koninklijke Philips N.V. | Filed August 2025 | US + India national phase | Priority: EP24196384

---

## Hackathons

**Gauntlet — Flip the Switch Hackathon by WeMakeDevs** *(Nov 2026)* · [GitHub](https://github.com/ShivVIT2019/gauntlet) · [Demo](https://youtu.be/-jGNKbCzvKI)
Team-chat workflow on Switch where Codex, Claude Code, and OpenCode agents work on the same coding task in parallel, each in isolated Git worktrees, coordinated by an orchestrator in a Mattermost channel. Rule-based referee re-runs the merge-base test suite on every branch and disqualifies branches that change, delete, or skip tests.

**Tessera — Buffer Commit** *(Nov 2026)*
Private repo, available on request.

---

## Currently Open To

- Full-time ML/AI Engineer roles (January 2027 start)
- OPT work authorization — no sponsorship needed immediately
