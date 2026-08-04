<div align="center">

<!-- Dynamic typing header -->
[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=1000&color=2F81F7&center=true&vCenter=true&width=700&lines=Lamonte+Smith+%7C+Senior+SDRE+%40+General+Motors;AV+Security+%7C+OT+%7C+Wireless+Infrastructure;Building+at+the+Intersection+of+AI+%26+Autonomy)](https://git.io/typing-svg)

</div>

---

<div align="center">


**Senior Software Design Release Engineer · General Motors Advanced Infotainment, Compute & Connectivity · Milford, MI**  
*20+ years spanning Automotive · Telecommunications · Information Technology*

</div>

---

## About

I work at the intersection of **AI/ML**, **cybersecurity**, **operational technology (OT)**, **autonomous vehicle systems**, and **wireless infrastructure (5G/6G/V2X)**. I am a Senior Software Design Release Engineer at General Motors Advanced Infotainment, Compute & Connectivity in Milford, MI. 

I am continuously learning — building agentic AI systems, RAG pipelines, and multi-agent workflows across several programs simultaneously. This repository is a reflection of that ongoing journey, not a finished product.

---

## Core Domains

| Domain | Focus |
|--------|-------|
| 🤖 **Agentic AI & Multi-Agent Systems** | n8n A2A workflows, LLM orchestration, tool-use pipelines |
| 🔐 **AI Cybersecurity & OT Security** | Evasion-based attack modeling, OT threat modeling, security-by-design |
| 🚗 **Autonomous Vehicle Security** | CPS threat surfaces, V2X, CARLA/ROS simulation environments |
| 📡 **Wireless & Telecom Infrastructure** | 5G/6G enablement, V2X connectivity, edge AI |
| 🏭 **IT/OT Convergence** | Industrial control systems, OT network security, resilience engineering |
| 📊 **RAG & Knowledge Systems** | ChromaDB, Pinecone, BM25 hybrid search, vector pipelines |

---

## Featured Projects

### 🧠 [AI-Powered Hiring Intelligence System](https://github.com/LSmithPMP/hiring-intelligence-system) — Capstone 2, Interview Kickstart
> 9-agent multi-agent pipeline for engineering talent acquisition insights. Specialized agents analyze sourcing quality, rejection patterns, interviewer load, offer trends, pipeline health, cost optimization, and real-time market compensation. RAG-grounded via ChromaDB, evaluated by LLM-as-judge, with two published n8n workflows and a Streamlit dashboard. All 20 security risks driven to LOW residual. Runs end-to-end for under one cent per full pipeline run.

**Stack:** `LangChain` `OpenAI` `ChromaDB` `n8n Cloud` `FastAPI` `Streamlit` `Pydantic`  
**Docs:** [Architecture](https://github.com/LSmithPMP/hiring-intelligence-system/blob/main/docs/IKCapstone2ArchitectureDocument_LSmith.docx) · [PRFAQ](https://github.com/LSmithPMP/hiring-intelligence-system/blob/main/docs/PRFAQ.md) · [Security Matrix](https://github.com/LSmithPMP/hiring-intelligence-system/blob/main/docs/IKCapstone2_SecurityRiskMatrix_LSmith.docx)

---

### 📊 [LLM Optimization Benchmark — Zero-Shot to LoRA](https://github.com/LSmithPMP/ik-agentic-ai-assignments) — Week 7, Interview Kickstart
> Benchmarks a customer support ticket classifier across four approaches: zero-shot GPT-4o-mini (92.9%), few-shot GPT-4o-mini (92.9%, 37% faster), few-shot GPT-4o (100%), and LoRA fine-tuning of SmolLM2-1.7B on a T4 GPU (78.6%). Generates real cost, accuracy, and latency data for build-vs-buy decisions. LoRA adapter: 12.6MB vs 3.4GB full model — 270x compression.

**Stack:** `OpenAI API` `HuggingFace Transformers` `PEFT/LoRA` `4-bit Quantization` `Google Colab T4`

---

### 🔁 [LLMOps Loop — Evaluating & Operationalizing Agents](https://github.com/LSmithPMP/ik-agentic-ai-assignments) — Week 6, Interview Kickstart
> Implements the full LLMOps feedback loop on a signup email agent: inspect baseline behavior, improve prompts, expand golden dataset, evaluate with DeepEval (ExactMatch, GEval, custom LLM-as-judge). LangSmith tracing integrated for online evaluation. 20-scenario golden dataset at 75% pass rate.

**Stack:** `LangChain` `LangSmith` `DeepEval` `OpenAI GPT-4o-mini` `Python`

---

### 🧠 [Digital Twin — RAG-Powered AI Chatbot](https://github.com/LSmithPMP/digital-twin)
> Personal AI digital twin built with GPT-4o, ChromaDB + BM25 hybrid retrieval, and Gradio. Security-by-design architecture with dedicated input validation, output filtering, and rate limiting. 23 biography sections, 188 retrievable chunks. Deployed to Hugging Face Spaces.

**Stack:** `Python` `GPT-4o` `ChromaDB` `BM25` `Gradio` `Hugging Face`  
**Live:** [huggingface.co/spaces/LSmithPMP/digital-twin](https://huggingface.co/spaces/LSmithPMP/digital-twin)

---

### 🔐 [Cybersecurity Threat Intelligence MCP Server](https://github.com/LSmithPMP/ik-agentic-ai-assignments)
> Node.js MCP server exposing five cybersecurity tools: search_iocs, lookup_cve, threat_actor_profile, map_ttps, get_risk_score. Zod input validation, token-bucket rate limiter, deny-by-default tool set, zero outbound HTTP. Full PRD, Risk Matrix, and architecture diagram included.

**Stack:** `Node.js` `MCP Protocol` `Zod` `TypeScript` `Rate Limiting`

---

### 🌐 [Travel Weather Comparator — Multi-Agent A2A System](https://github.com/LSmithPMP/travel-weather-comparator)
> 16-node n8n Agent-to-Agent workflow with parallel Weather and Travel agent microservices, weighted scoring, and ranked city recommendations. Full security hardening to all-LOW residual risk. PRD v2.0 with security architecture section.

**Stack:** `n8n` `A2A Protocol` `Multi-Agent` `Weather APIs` `Python`

---

### 🏦 [BankCo Premium Retention Agent](https://github.com/LSmithPMP/ik-agentic-ai-assignments)
> AI-powered customer retention system with three parallel implementations — n8n workflow orchestration, React demo interface, and Python backend — demonstrating production-grade agent design patterns.

**Stack:** `n8n` `React` `Python` `LLM Orchestration` `GPT-4o`

---

### 🎙️ [Voice AI RAG Assistant — Jerry Multi-Agent](https://github.com/LSmithPMP/jerry-multi-agent-assistant)
> Voice-enabled RAG assistant with multi-agent orchestration via n8n. Integrates Whisper for speech recognition, Pinecone for vector retrieval, and ElevenLabs for voice synthesis.

**Stack:** `Python` `Whisper` `Pinecone` `GPT-4o` `ElevenLabs` `Streamlit`

---

### 🏥 [Healthcare Multi-Agent System](https://github.com/LSmithPMP/healthcare-multi-agent)
> Agentic AI system orchestrating across five structured healthcare datasets via n8n, demonstrating multi-source agent coordination for clinical decision-support workflows.

**Stack:** `n8n` `Multi-Agent` `Google Sheets` `GPT-4o` `Python`

---

### 📈 [Intelligent Systems Performance Suite — Tableau](https://public.tableau.com/app/profile/lamonte.smith/vizzes)
> Four-panel ML performance dashboard: Digital Twin Drift & Anomaly Detection, 5G/V2X Network Inference Latency, AV Sensor Fusion & Model Confidence, RAG & Agentic Pipeline Performance.

**Stack:** `Tableau Public` `ML Metrics` `5G/V2X` `AV Sensor Fusion` `RAG`

---

### 🔬 AV/OT Security ML Research Framework — Dissertation, In Progress
> Simulation scaffold for dissertation research: evasion-based and perturbation-based attack modeling against ML models embedded in autonomous vehicle OT systems, using CARLA, ROS, SUMO, and OMNeT++ environments.

**Stack:** `Python` `CARLA` `ROS` `SUMO` `OMNeT++` `PyTorch`

---

## Tech Stack

### AI / ML
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![Hugging Face](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat&logo=huggingface&logoColor=black)

### Agentic & Orchestration
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat&logo=n8n&logoColor=white)
![Gradio](https://img.shields.io/badge/Gradio-F97316?style=flat&logo=gradio&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)

### Vector & Retrieval
![ChromaDB](https://img.shields.io/badge/ChromaDB-1B1B2F?style=flat&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=flat&logo=pinecone&logoColor=white)

### Development
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/VSCode-007ACC?style=flat&logo=visualstudiocode&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)

### Simulation & Research
![ROS](https://img.shields.io/badge/ROS-22314E?style=flat&logo=ros&logoColor=white)
![CARLA](https://img.shields.io/badge/CARLA_Simulator-0078D4?style=flat&logoColor=white)

---

## Credentials & Affiliations

| Credential | Issuer |
|-----------|--------|
| 🎓 DBA Candidate — AIML Leadership | Walsh College, Troy MI |
| 🎓 PhD Candidate — Technology / Cybersecurity | Walsh College, Troy MI |
| 📋 Project Management Professional (PMP) | PMI |
| ⚡ Agile Certified Practitioner (PMI-ACP) | PMI |
| ⚙️ Design for Six Sigma Black Belt (DFSS) | General Motors |
| 🤖 AI Product Manager Nanodegree | Udacity |
| 🏛️ Teaching Certificate in Higher Education Pedagogy | Harvard Derek Bok Center |
| 🧪 Applied Agentic AI Program (Capstone 2) | Interview Kickstart |
| 🤖 Generative AI Mastermind | Outskill |
| 🏅 AI Engineer 6-Week Sprint | SuperDataScience |

---

## GitHub Stats

<div align="center">

![Lamonte's GitHub Stats](https://github-readme-stats.vercel.app/api?username=LSmithPMP&show_icons=true&theme=github_dark&hide_border=true&count_private=true&include_all_commits=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=LSmithPMP&layout=compact&theme=github_dark&hide_border=true)

</div>

---

## Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lamonte-smith-7518b4248/)
[![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/LSmithPMP)
[![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)](https://www.kaggle.com/lamontesmith)
[![n8n Workflows](https://img.shields.io/badge/n8n_Workflows-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)](https://lamontesmith.app.n8n.cloud/projects/vGmn0vDV6EIUJHZW/workflows)
[![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)](https://public.tableau.com/app/profile/lamonte.smith/vizzes)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:lamontesmithpmp@gmail.com)

</div>

---

<div align="center">
<sub>Dual Doctoral Candidate · DBA (AIML Leadership) + PhD (Cybersecurity) · Walsh College · Expected December 2027</sub>
</div>
