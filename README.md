# Hi, I'm Avnish 

AI/ML Engineer focused on LLMs, RAG systems, and agentic architectures. Final-year B.Tech CSE student, currently building production-grade AI systems and applying for AI/ML Engineer roles in India, remote, and Japan.

## What I'm working on

**[AegisOps AI](https://github.com/Avnish1505/aegisops-ai)** — A deterministic safety-gated AI system for crisis decision support. Combines a rule-based safety layer with an LLM/RAG incident commander, FastAPI + WebSocket backend, and a React dashboard with human-approval workflows. Unit and API acceptance tests run in CI alongside Ruff and mypy. Currently extending it with an Implementation Integrity Analyzer to detect plan-vs-execution mismatches in AI coding agents.

**[Cancer Fusion AI](https://github.com/Avnish1505/cancer-fusion-ai)** — Multimodal skin cancer classifier combining ResNet50 image features with patient metadata (HAM10000 dataset). Macro-F1 ~0.73, with Grad-CAM for explainability. Deployed as a FastAPI + React application.

**[omitbench](https://github.com/Avnish1505/Omitbench)** — A benchmark and deterministic detector for silent omissions in AI coding-agent patches. Built a 310-instance labelled corpus by mutating real merged commits across 8 Python libraries, so ground truth costs zero API spend. Headline result: a mid-tier LLM judge beats the deterministic detector overall (paired MCC −0.202, 95% CI excluding zero) — reported as the honest finding, not hidden. CI enforces a precision floor on every push.

**[AgentGrade](https://github.com/Avnish1505/agentgrade)** — An Agentforce agent for B2B order and returns operations, with a deterministic refund guardrail written in Agent Script, Apex actions for order lookup, return windows, refunds and escalation, and an external Python harness that scores routing, action-sequence and grounding failures through the Agent API. A 70-case suite ran with zero errors at 6.3s p95 per full session. The main finding is a negative one: across 93 test sessions the deterministic return-window check never fired, so the gate is correct as written but unreachable at runtime in this org. Metrics that depend on the platform's session traces are reported as untestable rather than given a fake pass rate, and a Streamlit dashboard shows them the same way.

**[CineMind AI](https://github.com/Avnish1505/cinemind-ai)** — A PyTorch two-tower recommender trained and evaluated offline on MovieLens-1M with point-in-time, leakage-audited features. With a learnable item ID embedding it reaches Recall@10 of 0.048–0.052 across three seeds against 0.037 for an item-item kNN baseline, while still leaning on popularity more than kNN does, which is listed as an open gap. An earlier headline number was retracted after an oracle upper bound exposed a feature leak, and the fix log keeps every correction. A FastAPI feature store and FAISS serving path run on a synthetic fixture, with 34 tests in CI.

**[Startup Success Predictor](https://github.com/Avnish1505/startup-success-predictor)** — ML + generative AI tool that estimates startup success probability and generates strategic insights, combining a trained classifier with LLM-based reasoning.

## Background

- Research paper, *"Emergence of Artificial Intelligence in Law and Legal Technology,"* accepted at ADG 2026 International Conference
- Learning Japanese alongside my technical work, as part of applying to roles in Japan

## Skills

![Python](https://img.shields.io/badge/-Python-black?style=flat-square&logo=python)
![JavaScript](https://img.shields.io/badge/-JavaScript-black?style=flat-square&logo=javascript)
![PyTorch](https://img.shields.io/badge/-PyTorch-black?style=flat-square&logo=pytorch)
![Scikit--learn](https://img.shields.io/badge/-Scikit--learn-black?style=flat-square&logo=scikitlearn)
![XGBoost](https://img.shields.io/badge/-XGBoost-black?style=flat-square)
![LangChain](https://img.shields.io/badge/-LangChain-black?style=flat-square)
![ChromaDB](https://img.shields.io/badge/-ChromaDB-black?style=flat-square)
![pandas](https://img.shields.io/badge/-pandas-black?style=flat-square&logo=pandas)
![NumPy](https://img.shields.io/badge/-NumPy-black?style=flat-square&logo=numpy)
![FastAPI](https://img.shields.io/badge/-FastAPI-black?style=flat-square&logo=fastapi)
![Django](https://img.shields.io/badge/-Django-black?style=flat-square&logo=django)
![React](https://img.shields.io/badge/-React-black?style=flat-square&logo=react)
![Docker](https://img.shields.io/badge/-Docker-black?style=flat-square&logo=docker)
![Git](https://img.shields.io/badge/-Git-black?style=flat-square&logo=git)
![Linux](https://img.shields.io/badge/-Linux-black?style=flat-square&logo=linux)
![Japanese](https://img.shields.io/badge/-日本語_(learning)-black?style=flat-square)

## Find me

- Portfolio: [avnishsingh.app](https://homepage.avnishsingh150606.workers.dev/en)
- LinkedIn: [avnish-singh-a94772309](https://linkedin.com/in/avnish-singh-a94772309)
