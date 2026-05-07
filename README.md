<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=120&section=header" width="100%"/>

</div>

<div align="center">

```
╔═══════════════════════════════════════════════════════════════╗
║                                                               ║
║        KANHAYYA GUPTA  ·  AI / ML ENGINEER                   ║
║        Building systems that think, reason & act             ║
║                                                               ║
╚═══════════════════════════════════════════════════════════════╝
```

[![LinkedIn](https://img.shields.io/badge/LinkedIn-kanhayya--gupta-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kanhayya-gupta/)
[![Email](https://img.shields.io/badge/Email-kanhacet@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kanhacet@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-kanhaiya--98-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/kanhaiya-98)
[![Location](https://img.shields.io/badge/Mumbai-India-FF6B35?style=for-the-badge&logo=googlemaps&logoColor=white)](https://maps.google.com/?q=Mumbai,India)

</div>

---

## `> whoami`

```python
class KanhayyyaGupta:

    role        = "GenAI & Agentic AI Engineer"
    company     = "Pixels Creative Technologies"
    education   = "B.Tech IoT — Thakur College of Engineering, Mumbai (2nd Year)"
    focus       = ["LLM Systems", "Agentic AI", "MLOps", "Production ML"]

    achievements = {
        "hackathons_won"    : 4,
        "national_finalist" : 19,
        "funded_startup"    : "Eternia — ₹1.2L Parul University Incubation",
        "times_mentored"    : "3x National Hackathon Mentor",
        "times_judged"      : "1x Hackathon Judge",
        "publications"      : ["Managing Editor @ BYTE Magazine",
                               "Co-Editor @ ThingTech Magazine"],
        "connections"       : "500+ LinkedIn"
    }

    currently_building = "Agentic AI systems that ship to production, not notebooks"
    learning           = ["DSA", "System Design", "LLM Fine-tuning (LoRA/QLoRA)"]
    philosophy         = "Build fast. Deploy faster. Make it matter."
```

---

## `> ls ./achievements`

<div align="center">

| 🏆 Achievement | 📍 Platform | 🎯 Details |
|---|---|---|
| **1st Place** | Zenith '25 AWS Hackathon | National Level · Team Hackstronauts |
| **1st Place** | AI Hackathon VIT Bhopal | Best AI Innovation |
| **1st Place** | ADAPPT 4.0 Hackathon | National Level |
| **1st Place** | AshnaAI Hackathon 2025 | AI Systems Track |
| **International Finalist** | Cyber Cypher 2025 | Global Competition |
| **National Finalist** | PVG HackHub 2025 | Top 10 / 400+ Teams |
| **Internal Winner** | Smart India Hackathon 2025 | SIH Official Round |
| **3× Mentor** | National Hackathons | Mentored competing teams |
| **1× Judge** | Hackathon Panel | Technical Evaluation |
| **₹1.2L Seed Funded** | Parul University Incubation | Eternia Platform |
| **19× National Finalist** | Various Competitions | Consistent top performer |

</div>

---

## `> cat ./experience.log`

### 🔷 AI Engineer — Pixels Creative Technologies *(Jan 2025 – Present)*
> *Production AI systems, not prototypes.*
- Built **RAG chatbot** on company's live website using LangChain + FAISS → **~40% reduction in manual support overhead**
- Architected **multi-agent e-commerce workflows** (CrewAI + LangGraph): auto-checkout agents, autonomous product recommendation flows
- Built AI-driven web scraping + content generation systems eliminating repetitive catalog update tasks

### 🔷 AI Engineer — OptiReachTech *(Oct 2024 – Dec 2024)*
> *Quantitative trading at scale.*
- Engineered **algorithmic trading strategies** using LangGraph pipelines with RSI, MACD, Bollinger Bands signal generation
- Built **multi-agent orchestration system** on FastAPI handling **500+ concurrent requests** · **40% cost reduction** · sub-200ms latency
- Set up AWS EC2 CI/CD (GitHub Actions) for zero-downtime trading strategy deployment

---

## `> ls ./projects --detailed`

---

### 🏥 [Hospi-Track](https://github.com/kanhaiya-98/HospiTrack-UN-SDG-3) — Hospital Ward Intelligence Platform
> *UN SDG 3 · React + FastAPI + LangGraph + Supabase*

Real-time hospital bed occupancy platform solving India's **0.6 beds per 1,000 people** visibility crisis. When AIG Hospitals replaced 74 Excel sheets with a system like this, admission TAT dropped **65%** and bed turnover improved **11%**.

```
┌─────────────────────────────────────────────────────────┐
│  Live Bed Board  →  Patient Flow  →  Outbreak Intel     │
│         ↓                                               │
│  BedPulse AI Engine (5-node LangGraph)                  │
│  RandomForest + Gemini LLM → 24h capacity forecast      │
└─────────────────────────────────────────────────────────┘
```

**Stack:** React 18 · FastAPI · LangGraph · Supabase Realtime WebSockets · scikit-learn · Google Gemini

**Key numbers:** 8-table PostgreSQL schema · 3 forecast scenarios · <200ms AI response · RLS on all tables

---

### 🌌 [Eternia](https://github.com/kanhaiya-98/Eternia-Anonymous-Institutional-Wellbeing-Platform) — Anonymous Student Wellbeing Platform
> *🏆 Won AI Hackathon VIT Bhopal · 💰 ₹1.2L Seed Funded · Next.js 15 + Supabase + Agora RTC*

Built for the **38 students who die by suicide in India every single day.** A full-stack mental health SaaS with structural anonymity — role-based access, real-time crisis escalation, and zero-identity voice rooms.

```
Student (anonymous) ──► Doctor ──► SPOC (live alert <1s) ──► Admin
        ↑                                    ↑
   BlackBox Voice              Supabase Realtime Broadcast
   (Agora RTC, 0 identity)     (sub-second escalation)
```

**Stack:** Next.js 15 · TypeScript · Supabase · Agora RTC SDK · AES-256-GCM · shadcn/ui

**Recognition:** CBSE-aligned · UGC-compliant · DPDP Act 2023 · Supreme Court Guidelines

---

### 🚀 [LogiSense AI](https://github.com/kanhaiya-98/LogiSense-logistics-AI-Unified-Platform-) — Agentic Logistics OS
> *🌐 International Finalist — Cyber Cypher 2025 · FastAPI + LangGraph + LightGBM*

10-module AI logistics platform with Observer → Reasoner → Actor agentic pipeline, blockchain audit trail, and full ML explainability via SHAP.

```
Observer (Isolation Forest) → Reasoner (DAG BFS) → Actor (Carrier Subbing)
         ↓
ZenDec (TOPSIS routing) · ZenRTO (LightGBM fraud) · ZenETA (XGBoost p50/p90/p99)
         ↓
F9 Blockchain (Polygon · Merkle Trees) · F10 LangGraph Synthesis
```

**Stack:** FastAPI · LangGraph · LightGBM · XGBoost · SHAP · Polygon Web3.py · Redis · React

---

### 💊 [Smart Pharmacy Hub](https://github.com/kanhaiya-98/Smart-Pharmacy-Management-System) — AI Pharmacy OS
> *🥇 National Winner Zenith '25 AWS Hackathon · FastAPI + LangChain + Gemini 2.0*

AI-powered pharmacy management for India's **10.6 lakh independent pharmacies** running on registers and memory. Predictive inventory, outbreak intelligence, drug interaction checking, and autonomous supplier negotiation.

```
Gemini 2.0 Conversational AI ──► Natural language → pharmacy actions
XGBoost Demand Forecasting   ──► 6-month inventory predictions
SafeDose Drug Checker        ──► Multi-drug interaction analysis
Supply Chain Automation      ──► SerpAPI + Gmail API negotiation
```

**Stack:** React 18 · FastAPI · LangChain · Gemini 2.0 · XGBoost · Supabase · TanStack Query

**Performance:** <200ms API latency · 95+ Lighthouse · Vercel + Render deployed

---

## `> cat ./skills.json`

```json
{
  "agentic_ai_llms": [
    "LangChain", "LangGraph", "CrewAI",
    "RAG", "Multi-Agent Orchestration",
    "Hugging Face", "LoRA / QLoRA",
    "OpenAI API", "Gemini API"
  ],
  "ml_dl": [
    "PyTorch", "TensorFlow", "scikit-learn",
    "XGBoost", "LightGBM", "SHAP",
    "RandomForest", "Isolation Forest"
  ],
  "backend_infra": [
    "FastAPI", "WebSockets", "Microservices",
    "Redis", "Docker", "Kubernetes",
    "AWS (ECS · Lambda · EC2 · S3)",
    "CI/CD (GitHub Actions)", "NGINX"
  ],
  "frontend_dbs": [
    "Next.js 15", "React 18", "TypeScript",
    "Tailwind CSS", "PostgreSQL",
    "Supabase", "FAISS", "ChromaDB"
  ],
  "currently_learning": [
    "DSA (Striver SDE Sheet)",
    "Python Internals + OOPs Deep Dive",
    "ML System Design",
    "LLM Fine-tuning (QLoRA)"
  ]
}
```

---

## `> cat ./github_stats`

<div align="center">

![Kanhayya's GitHub Stats](https://github-readme-stats.vercel.app/api?username=kanhaiya-98&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=kanhaiya-98&layout=compact&theme=tokyonight&hide_border=true&langs_count=6)

![GitHub Streak](https://streak-stats.demolab.com?user=kanhaiya-98&theme=tokyonight&hide_border=true)

</div>

---

## `> ./connect.sh`

<div align="center">

*Open to internships, full-time AI/ML roles, and collaborations on systems that ship.*

**FAANG · MAANG · High-growth AI startups · Research teams**

[![LinkedIn](https://img.shields.io/badge/Let's_Connect-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/kanhayya-gupta/)
[![Email](https://img.shields.io/badge/Reach_Out-Email-EA4335?style=for-the-badge&logo=gmail)](mailto:kanhacet@gmail.com)

---

*"The bed that saves a life is often not the one that doesn't exist. It's the one nobody could see."*
*— Hospi-Track README*

</div>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=80&section=footer" width="100%"/>
</div>
