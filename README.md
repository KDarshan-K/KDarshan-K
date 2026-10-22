<div align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=4DA8F7&center=true&vCenter=true&multiline=true&width=550&lines=Hi%2C+I'm+Darshan+Kagadal+%F0%9F%91%8B;Backend+Systems+%26+Applied+AI%2FML" alt="Typing SVG" />
  </a>



  <p>Final-year CS undergraduate specializing in low-latency backend services, multi-agent LLM orchestration, and deep reinforcement learning.</p>

  <a href="https://www.linkedin.com/in/darshankagadal/">
    <img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:darshankagadalk@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
</div>

---

## 🔥 Featured Projects (Top 3)

### 🤖 [Multi-Agent Financial Research Pipeline](https://github.com/KDarshan-K)
7-agent autonomous financial research engine built on a custom, zero-dependency graph execution framework.
- **Custom Graph Orchestration:** Engineered a `stdlib`-only graph execution engine supporting 7 stateful agents (*Orchestrator, Market, News, Search, RAG, Analyst, Critic*) with conditional edges and fan-out/converge execution.
- **Unified MCP Tool Layer:** Routed all agent actions through a single Model Context Protocol (MCP)-style registry integrating live market data, company news, **SEC EDGAR filings**, and web search.
- **Self-Correcting RAG:** Built a bounded critic-driven revision loop and a custom TF-IDF/cosine-similarity retriever producing source-attributed analyst reports with full run checkpointing and resume support.
- **Stack:** `Python` · `Custom Agent Graph` · `MCP` · `RAG` · `LLMs`

### ☁️ [Secure AI Cloud Resource Optimization (Deep RL)](https://github.com/KDarshan-K)
Closed-loop Deep Reinforcement Learning cloud scheduler benchmarked on 100-host Google, Alibaba, and AWS workload traces.
- **Multi-Objective PPO Scheduler:** Trained DQN, PPO, and DDPG agents optimizing CPU utilization, energy, SLA compliance, cost, and host trust—achieving **92% CPU utilization** (a **+24% improvement** over FCFS) and a **3% SLA violation rate**.
- **Runtime Threat Mitigation:** Built a security-aware task placement layer that dynamically redirected **96.4% of sensitive workloads** away from compromised hosts within **2.3 seconds** under simulated attacks.
- **Real-Time Inference:** Deployed the trained RL policy as a **FastAPI** inference service paired with a **React** monitoring dashboard for live cluster visibility.
- **Stack:** `PyTorch` · `Stable-Baselines3` · `OpenAI Gym` · `CloudSim Plus` · `FastAPI` · `React`

### 🚚 [Unified Global Logistics Hub](https://github.com/KDarshan-K/Unified-logistics)
Full-stack logistics platform featuring sub-2ms geospatial querying and an AI-powered natural language admin engine.
- **High-Throughput Document Model:** Engineered a MongoDB schema achieving **sub-2ms query latency (1.66ms avg)** across both single-document lookups and full collection fetches.
- **Real-Time Geospatial Dispatch:** Implemented nearest-driver assignment using MongoDB `$near` within a 10km radius, paired with 3-second live shipment polling.
- **Text-to-NoSQL Admin Panel:** Integrated **Groq (Llama 3.1)** to compile plain-English operational questions directly into executable MongoDB aggregation pipelines against live data.
- **Stack:** `FastAPI` · `MongoDB` · `Groq (Llama 3.1)` · `Jinja2` · `Postman`

<details>
<summary><b>📂 View More Projects (Quant ML, Adversarial CV & Financial RAG)</b></summary>
<br/>

#### 📈 [ForexTrendML: Macro-Quant Forecasting & Backtesting Engine](https://github.com/KDarshan-K/ForexTrendML-Boxbox)
- **Automated Multi-Frequency ETL:** Ingested real-time FX prices (Yahoo Finance) and asynchronous macro indicators (FRED API), reconciling daily and monthly time-series via forward-filling and scaling across a modular 4-layer architecture.
- **Quantitative Signal & Backtesting:** Trained an **XGBoost** classifier for 5-day USD/INR directional forecasting with confidence thresholding, evaluating Total Return, Buy & Hold, and **Sharpe Ratio** inside an interactive **Streamlit** dashboard.
- **Stack:** `Python` · `XGBoost` · `Scikit-Learn` · `Pandas` · `Streamlit` · `REST APIs`

#### 🛡️ [Adversarial CAPTCHA Breaking & Defense System](https://github.com/KDarshan-K)
- **Multi-Head CNN Architecture:** Built a PyTorch CNN jointly predicting all 5 character positions across 36 classes in a single forward pass.
- **Attack & Hardening Pipeline:** Stress-tested the model using **FGSM** and **PGD ($L_\infty$)** adversarial attacks ($\epsilon \in [0, 0.3]$) and hardened checkpoints via adversarial training to quantify the robustness/accuracy trade-off.
- **Stack:** `PyTorch` · `CNNs` · `Adversarial ML (FGSM / PGD)`

#### 🔎 [FinRAG: Financial Document Processing Pipeline](https://github.com/KDarshan-K/FinRAG-boxbox)
- **Semantic Ingestion & Retrieval:** Built an automated pipeline using PyMuPDF and LangChain to clean and chunk 10-K filings into a **FAISS** vector store connected to a **Groq LLM** for low-latency Q&A.
- **Stack:** `Python` · `LangChain` · `FAISS` · `Groq` · `PyMuPDF`

</details>

---

## 💻 Tech Stack

**Languages**  
![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![C++](https://img.shields.io/badge/C++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white) ![C](https://img.shields.io/badge/C-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white) ![Bash](https://img.shields.io/badge/GNU_Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)

**AI, Agents & Machine Learning**  
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=pytorch&logoColor=white) ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white) ![LangGraph](https://img.shields.io/badge/LangGraph-0B5345?style=for-the-badge&logo=langchain&logoColor=white) ![MCP](https://img.shields.io/badge/MCP-000000?style=for-the-badge&logo=anthropic&logoColor=white) ![Groq](https://img.shields.io/badge/Groq-F55036?style=for-the-badge&logo=fastapi&logoColor=white) ![HuggingFace](https://img.shields.io/badge/Transformers-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black) ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white) ![XGBoost](https://img.shields.io/badge/XGBoost-1572B6?style=for-the-badge) ![Stable-Baselines3](https://img.shields.io/badge/Stable--Baselines3-2E8B57?style=for-the-badge) ![OpenAI Gym](https://img.shields.io/badge/OpenAI_Gym-0081A7?style=for-the-badge&logo=openai&logoColor=white)

**Data Science & Analytics**  
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black) ![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge) ![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

**Backend, Databases & Vector Stores**  
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi) ![Streamlit](https://img.shields.io/badge/Streamlit-%23FE4B4B.svg?style=for-the-badge&logo=streamlit&logoColor=white) ![Jinja](https://img.shields.io/badge/Jinja-B41717?style=for-the-badge&logo=jinja&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white) ![FAISS](https://img.shields.io/badge/FAISS-00599C?style=for-the-badge&logo=meta&logoColor=white) ![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6F00?style=for-the-badge)

**Cloud, DevOps & Tools**  
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white) ![Oracle](https://img.shields.io/badge/Oracle_Cloud-F80000?style=for-the-badge&logo=oracle&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-%232496ED.svg?style=for-the-badge&logo=docker&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black) ![CloudSim Plus](https://img.shields.io/badge/CloudSim_Plus-007396?style=for-the-badge) ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white) ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

---

## 🏆 Highlights, Publications & Certifications
- 📄 **IEEE TEMCAT 2026:** Selected for presentation — *Secure Cloud Resource Optimization using Machine Learning and Reinforcement Learning*.
- 📈 **Research Author (2025):** *Macro-Quant Forecasting of USD/INR Exchange Rates using Machine Learning & Macroeconomic APIs*.
- 🏅 **Hackaphasia '24 (IEEE BMSCE):** Led team to a **Top 5 Finish** out of 125 teams at a national-level hackathon.
- 🎖️ **Certifications:** Oracle Certified Professional: OCI Generative AI · AWS Cloud Essentials · Cisco Security Essentials.

---

## 📊 GitHub Activity

<div align="center">
  <img src="https://streak-stats.demolab.com/?user=KDarshan-K&theme=gotham&hide_border=true" alt="GitHub Streak" />
  <br/><br/>
  <img src="
