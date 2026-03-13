# Vishwajeet Adkine

**AI/ML Researcher & Systems Engineer** — building agentic AI platforms, interpretable security ML systems, and edge-deployed LLM infrastructure. Research focus: spectral theory of neural networks and AI safety.

BSc Artificial Intelligence applicant at **MBZUAI (2027)** · Stanford ML · DeepLearning.AI · Based in India

[![Portfolio](https://img.shields.io/badge/Research_Portfolio-Live-c0392b?style=flat-square)](https://my-portfolio-delta-weld-18.vercel.app/)
[![Trust Score Demo](https://img.shields.io/badge/Trust_Score_Demo-Deployed-3a6b5a?style=flat-square)](https://websitetrustscore.vishwajeetadkine705.workers.dev/)
[![Email](https://img.shields.io/badge/Email-Contact-2d4a6e?style=flat-square)](mailto:vishwajeetadkine705@gmail.com)

---

## What I Build

I work across the full stack of AI — from mobile apps and browser automation to multi-agent platforms and theoretical ML research. Everything is end-to-end and deployed, not just notebooks.

**Current focus:** Stremini AI ecosystem (15-agent workspace, AI keyboard, desktop automation agent, educational platform) and KhetiAI (agricultural AI for underserved Indian farmers).

---

## Repositories

| Repo | What's inside |
|------|--------------|
| [AI-Systems](https://github.com/983111/AI-Systems) | Stremini AI (15-agent workspace, StreminiIME keyboard, Electron automation agent, 517-topic Academy) + KhetiAI (crop disease detection, APMC price forecasting) |
| [Applied-AI-ML-Projects](https://github.com/983111/Applied-AI-ML-Projects) | DistilBERT fine-tuning (86.7%), character-level LSTM from scratch, CNN on CIFAR-10 (87.3%), 4-layer neural net in pure NumPy, Prompt Engineering Lab |
| [RESEARCH-work](https://github.com/983111/RESEARCH-work) | ML Scam Detector (94.96% acc, 28k URLs), Gradient Descent as a Dynamical System (interactive paper), Spectral Properties of Attention Matrices (interactive paper) |
| [AI-Projects](https://github.com/983111/AI-Projects) | STYFI (fashion AI + SDXL image enhancement), Scholira (scholarship RAG engine, TF-IDF from scratch), Zz-AI (voice-first desktop agent) |

---

## Selected Projects

**Stremini AI** — Cross-platform multi-agent AI ecosystem
- 15 specialized agents across Intelligence, Creation, Strategy, and Execution layers — each backed by a Cloudflare Worker and K2-Think-v2
- Token-streaming SSE pipeline with think-block gating and retry-with-backoff — ~60% reduction in perceived latency
- AI keyboard (StreminiIME) with 7 endpoints: autocomplete, tone rewrite, grammar, translation across 40+ languages
- Stremini Academy: 517 topics, 25 tracks, 6 tiers with XP/streak engine and custom LLM output parser

**KhetiAI / KhetiPlus** — Agricultural AI for Indian farmers
- Crop disease detection returning structured pathology reports (diagnosis, causal agent, treatment) via Gemini 2.5 Flash vision
- 3-month APMC mandi price forecasting with trend classification (rising / stable / falling)
- Dual-model architecture: Gemini 2.5 Flash for vision, K2-Think-v2 for reasoning — React 19 + Cloudflare Worker stack

**ML Scam Detector** — Interpretable security pipeline
- 16 hand-crafted features + Logistic Regression with Platt calibration — 100% recall, 95% precision on stratified dataset
- Malicious URL detector: 94.96% accuracy on 28,000-URL dataset (URLhaus + Tranco Top 1M)
- Three-tier ensemble: heuristics → ML → LLM with confidence-based routing, cutting LLM cost by ~90%
- [Live endpoint →](https://websitetrustscore.vishwajeetadkine705.workers.dev/)

**STYFI** — Fashion AI backend
- Outfit intelligence via Gemini 2.5 Flash + two-stage product image enhancement (segmentation → SDXL img2img)

**Scholira** — Scholarship retrieval engine
- TF-IDF built from scratch (tokeniser, IDF, cosine similarity — no external ML library) matching students to 110 global scholarships

**Zz Voice OS** — Desktop AI agent
- Tiered LLM dispatch: regex intent → LRU cache → daily token quota → Groq Llama 3.3-70b → fallback. HS256 JWT and Supabase REST client built from scratch

---

## Research

**Spectral Properties of Attention Matrices in Transformers** — Independent research
- Proved power-law singular value decay (σᵢ ≈ C/iᵅ, α ∈ [0.5, 1.0]) and derived Frobenius norm O(√n) / spectral norm O(log n) scaling
- Formalised sparsity-rank duality via attention entropy: effective rank ≈ exp(H(attn))
- [Interactive paper →](https://my-portfolio-delta-weld-18.vercel.app/)

**Gradient Descent as a Dynamical System** — Independent research
- Derived Jacobian stability conditions via spectral radius ρ(I − η·H), proved optimal learning rate η* = 2/(λ_min + λ_max)
- Published as interactive HTML paper with live bifurcation diagrams

**Hybrid Interpretable Scam Detection** — Flagship research manuscript
- Unified ensemble of supervised learning, LLM semantic analysis, and rule-based heuristics with explainability and deployment realism

**AI Safety & Prompt Injection Defense** — Applied research
- Pattern-based detection with regex matching, input sanitization, and layered system-prompt hardening — deployed in Stremini AI production

---

## ML Experiments

| Project | Method | Result |
|---------|--------|--------|
| IT Support Classifier | DistilBERT fine-tuning (HuggingFace) | 86.7% test accuracy · 5 classes · 300 samples |
| CNN on CIFAR-10 | 1.2M param CNN, batch norm, OneCycleLR, label smoothing | 87.3% in 30 epochs |
| Character-Level LSTM | Pure NumPy — all gates, BPTT, gradient clipping, Adam | Zero external ML framework |
| Neural Net from Scratch | 4-layer MLP, pure NumPy, mini-batch SGD | Zero autograd |
| Prompt Engineering Lab | 8 A/B experiments, LLM-as-judge scoring (4-axis rubric) | K2-Think-v2 · exportable JSON/Markdown |

---

## Tech Stack

**ML & Research** — PyTorch · HuggingFace Transformers · scikit-learn · NumPy · SHAP · TF-IDF · Platt Calibration · BPTT

**LLM & Inference** — MBZUAI K2-Think-v2 · Gemini 2.5 Flash · Groq Llama 4 Scout · SSE Streaming · Multi-Agent Orchestration · Prompt Engineering · RAG

**Infrastructure** — Cloudflare Workers · FastAPI · Flask · Supabase · Electron · Playwright

**Languages** — Python · JavaScript / TypeScript · Kotlin · Dart (Flutter)

**Platforms** — Android (Accessibility Services, Custom IME) · Desktop (Electron) · Web (React 19, Vite) · Mobile (Flutter)

---

## Certifications & Background

- Stanford University — Machine Learning
- DeepLearning.AI — Deep Learning Specialization
- MBZUAI BSc Artificial Intelligence applicant (2027 intake)

**Research interests:** interpretable ML for security · spectral theory of neural networks · LLM safety & prompt injection defence · agentic AI systems · AI for underserved South Asian markets

---

<sub>All research and projects authored independently · Portfolio: [my-portfolio-delta-weld-18.vercel.app](https://my-portfolio-delta-weld-18.vercel.app/)</sub>
