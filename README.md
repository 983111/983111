# Vishwajeet Adkine

**AI/ML Researcher & Systems Engineer** — building agentic AI platforms, interpretable security ML systems, and edge-deployed LLM infrastructure. Research focus: spectral theory of neural networks and AI safety.

[![Portfolio](https://img.shields.io/badge/Research_Portfolio-Live-c0392b?style=flat-square)](https://portfolio-vishwajeetadkine.vercel.app/)
[![Trust Score Demo](https://img.shields.io/badge/Trust_Score_Demo-Deployed-3a6b5a?style=flat-square)](https://websitetrustscore.vishwajeetadkine705.workers.dev/)
[![Email](https://img.shields.io/badge/Email-Contact-2d4a6e?style=flat-square)](mailto:vishwajeetadkine705@gmail.com)

---

## Repositories

| Repo | What's inside |
|------|--------------|
| [AI-Systems](https://github.com/983111/AI-Systems) | Stremini AI (15-agent workspace, StreminiIME keyboard, Electron automation agent, 517-topic Academy) + KhetiAI (crop disease detection, APMC price forecasting) |
| [Applied-AI-ML-Projects](https://github.com/983111/Applied-AI-ML-Projects) | DistilBERT fine-tuning (86.7%), character-level LSTM from scratch, CNN on CIFAR-10 (87.3%), 4-layer neural net in pure NumPy, Prompt Engineering Lab |
| [RESEARCH-work](https://github.com/983111/RESEARCH-work) | ML Scam Detector (94.96% acc, 28k URLs), Gradient Descent as a Dynamical System (interactive paper), Spectral Properties of Attention Matrices (interactive paper) |
| [AI-Projects](https://github.com/983111/AI-Projects) | STYFI (fashion AI + SDXL image enhancement), Scholira (scholarship RAG engine, TF-IDF from scratch), Zz-AI (voice-first desktop agent) |
| [Reinforcement-Learning](https://github.com/983111/Reinforcement-Learning) | AgentGrid — PPO autonomous navigation agent built from scratch in PyTorch |

---

## AI Systems & Projects

### Stremini AI — Cross-platform Multi-Agent AI Ecosystem
`github.com/983111/AI-Systems` · `kaggle.com/datasets/vishwajeetadkine/streminiai`

- 15 specialized agents across Intelligence, Creation, Strategy, and Execution layers — each backed by a Cloudflare Worker and K2-Think-v2
- Token-streaming SSE pipeline with think-block gating, in-flight promise deduplication, and retry-with-backoff — ~60% reduction in perceived latency
- Map-reduce document QA supporting 600k-character inputs with parallel chunk extraction, NOT RELEVANT filtering, and final synthesis pass
- AI keyboard (StreminiIME) with 7 endpoints: autocomplete, tone rewrite, grammar, translation across 40+ languages using dual-model routing
- Stremini Academy: 517 topics, 25 tracks, 6 tiers with XP/streak engine, custom LLM output parser, and full offline persistence
- Fine-tuned LLaMA 3 Instruct on curated Mobile Automation Dataset — BLEU-4: 0.78, Exact Match: 72%, Execution Success Rate: 68%; exported to ONNX and published to HuggingFace Hub
- Desktop hands-on-screen AI helper using Electron and K2-Think-v2 for contextual assistance and real-time inference

---

### KhetiAI (KhetiPlus) — Agricultural AI for Indian Farmers
`github.com/983111/AI-Systems`

- Agricultural AI platform for underserved Indian farmers — dual-model architecture (Gemini 2.5 Flash for vision, K2-Think-v2 for reasoning) on React 19 + Cloudflare Worker
- Crop disease detection returning structured pathology reports (diagnosis, causal agent, treatment) from base64 image input via Gemini vision
- 3-month APMC mandi price forecasting in JSON mode with trend classification (rising / stable / falling)
- Multi-agent Intelligence Hub covering pest migration, soil health, and agricultural advisory

---

### Elevated — Free AI-Powered Educational Platform (Non-Profit)

- Free AI-powered platform helping 200+ students improve SOPs, essays, and CVs using K2-Think-v2
- Students can discover global scholarships, find mentors from top universities, secure internships, and connect with research professors
- End-to-end guidance system for college applications, essay refinement, and career pathway planning — provided at no cost to students from underserved communities

---

### AgentGrid — PPO Autonomous Navigation Agent
`github.com/983111/Reinforcement-Learning`

- Built from-scratch Proximal Policy Optimization (PPO) with GAE on custom procedurally-generated GridWorld environment using PyTorch
- Shared MLP Actor-Critic architecture (2×128, Tanh) with 20,485 policy parameters; achieved 60% success rate on 10×10 grid after 300,000 timesteps
- Complete training infrastructure: rollout buffer, advantage estimation, PPO-clip surrogate loss, value function loss, and entropy regularization

---

### Android Automation AI — Fine-Tuned LLaMA Instruct
`huggingface.co/vishwajeet456`

- Fine-tuned LLaMA 3 Instruct converting natural language commands into executable Android automation scripts via ADB
- Designed specialized Mobile Automation Dataset with intent-labeled user queries paired with Android automation code
- BLEU-4: 0.78, Exact Match: 72%, Execution Success Rate: 68%; ONNX-exported inference pipelines for edge deployment

---

### ML Scam Detector — Interpretable Security Pipeline
`github.com/983111/RESEARCH-work` · DOI: 10.5281/zenodo.18988169 · [Live endpoint →](https://websitetrustscore.vishwajeetadkine705.workers.dev/)

- 16 hand-crafted features + Logistic Regression with Platt calibration — 100% recall, 95% precision on stratified dataset
- Malicious URL detector: 94.96% accuracy on 28,000-URL dataset (URLhaus + Tranco Top 1M) with FastAPI inference endpoint
- Three-tier ensemble: heuristics → ML → LLM with confidence-based routing, cutting LLM cost by ~90%

---

### STYFI — Fashion AI Backend
`github.com/983111/AI-Projects`

- Outfit intelligence via Gemini 2.5 Flash
- Two-stage product image enhancement pipeline: segmentation → SDXL img2img for high-quality results

---

### Scholira — Scholarship Retrieval Engine
`github.com/983111/AI-Projects`

- Serverless scholarship retrieval engine matching students to 110 global scholarships
- TF-IDF built entirely from scratch (tokeniser, IDF, cosine similarity) — no external ML library used

---

### Zz Voice OS — Voice-First Desktop AI Agent
`github.com/983111/AI-Projects`

- Voice-first AI OS in Electron with tiered LLM dispatch: regex intent → LRU cache → daily token quota → Groq Llama 3.3-70b → fallback
- HS256 JWT authentication and Supabase REST client built from scratch

---

### Silicon Scientist — Autonomous Lab Agent

- Autonomous lab-agent web application with data visualization, experiment orchestration, and hypothesis evolution tracking
- Built with React, Tailwind CSS, and Recharts

---

## Research

### Spectral Properties of Attention Matrices in Transformers
`github.com/983111/RESEARCH-work` · [Interactive paper →](https://portfolio-vishwajeetadkine.vercel.app/)

- Proved power-law singular value decay (σᵢ ≈ C/iᵅ, α ∈ [0.5, 1.0]) and derived Frobenius norm O(√n) / spectral norm O(log n) scaling
- Formalised sparsity-rank duality via attention entropy: effective rank ≈ exp(H(attn)), establishing expressivity-efficiency trade-offs with practical sparsity guidelines

---

### Gradient Descent as a Dynamical System
`github.com/983111/RESEARCH-work` · Interactive HTML paper

- Derived Jacobian stability conditions via spectral radius ρ(I − η·H); proved optimal learning rate η* = 2/(λ_min + λ_max) for quadratic convergence
- Published as interactive HTML paper with live bifurcation diagrams

---

### Persistent Memory Architectures for Human-like NPC Behavior

- Independent research on next-generation Game AI integrating RL, Memory Graphs, Vector Retrieval (HNSW), and Large Language Models
- Four-layer NPC intelligence architecture evaluated across 1,500+ simulated interaction episodes
- Memory-augmented RL agents achieved action entropy of 2.31 bits vs. 1.47 (RL-only) and 0.89 (scripted); player-perceived realism improved to 4.1/5.0 vs. 3.2/5.0 (RL-only) and 2.4/5.0 (scripted)
- Accepted at HPAIR (Harvard Project for Asian and International Relations)

---

### Hybrid Interpretable Scam Detection — Flagship Research Manuscript
DOI: 10.5281/zenodo.18988169

- Unified ensemble of supervised learning, LLM semantic analysis, and rule-based heuristics with explainability and deployment realism

---

### AI Safety & Prompt Injection Defense — Applied Research

- Pattern-based detection with regex matching, input sanitisation, and layered system-prompt hardening
- Deployed in Stremini AI production environment

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

**ML & Research** — PyTorch · HuggingFace Transformers · scikit-learn · NumPy · SHAP · TF-IDF · Platt Calibration · BPTT · ONNX · Optuna

**LLM & Inference** — MBZUAI K2-Think-v2 · Gemini 2.5 Flash · Groq Llama 4 Scout · LLaMA 3 Instruct · DistilBERT · SSE Streaming · Multi-Agent Orchestration · Prompt Engineering · RAG · Fine-tuning (LoRA/QLoRA) · Model Quantization

**Reinforcement Learning** — PPO · GAE · Gymnasium · Custom Environment Design · Actor-Critic Architectures

**Infrastructure** — Cloudflare Workers · FastAPI · Flask · Supabase · Electron · Playwright · CI/CD

**Languages** — Python · JavaScript / TypeScript · C++ · Kotlin · Dart (Flutter)

**Platforms** — Android (Accessibility Services, Custom IME) · Desktop (Electron) · Web (React 19, Vite, Tailwind CSS) · Mobile (Flutter)

---

## Online Presence

| Platform | Link |
|----------|------|
| Portfolio | [portfolio-vishwajeetadkine.vercel.app](https://portfolio-vishwajeetadkine.vercel.app/) |
| GitHub | [github.com/983111](https://github.com/983111) |
| HuggingFace | [huggingface.co/vishwajeet456](https://huggingface.co/vishwajeet456) |
| Kaggle | [kaggle.com/datasets/vishwajeetadkine/streminiai](https://kaggle.com/datasets/vishwajeetadkine/streminiai) |

---

<sub>All research and projects authored independently.</sub>
