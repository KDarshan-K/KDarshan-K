<div align="center">
  <a href="https://kdarshan-k.github.io/Personal-site">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1000&color=4DA8F7&center=true&vCenter=true&width=450&lines=Hi%2C+I'm+Darshan+Kagadal+%F0%9F%91%8B" alt="Typing SVG" />
  </a>

  <p><b>Final-year CS Undergraduate</b> building low-latency backend services, multi-agent LLM pipelines, and deep reinforcement learning systems.</p>

  <p>
    <a href="https://kdarshan-k.github.io/Personal-site">
      <img src="https://img.shields.io/badge/Portfolio-kdarshan--k.github.io-2563EB?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio" />
    </a>
    <a href="https://www.linkedin.com/in/darshankagadal/">
      <img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
    <a href="mailto:darshankagadalk@gmail.com">
      <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
    </a>
  </p>
</div>

> [!NOTE]
> **Currently:** Designing zero-dependency multi-agent orchestration (MCP), low-latency APIs, and Deep RL schedulers.  
> **Opportunities:** Open to **2027 SWE / Backend / Applied AI-ML** roles and internships. Explore my full work at **[kdarshan-k.github.io/Personal-site](https://kdarshan-k.github.io/Personal-site)**.

---

## 🔥 Featured Engineering Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🤖 <a href="https://github.com/KDarshan-K">Multi-Agent Financial Research</a></h3>
      <p>7-agent autonomous research pipeline built on a custom, <code>stdlib</code>-only graph execution engine supporting stateful nodes, conditional edges, and fan-out/converge execution.</p>
      <ul>
        <li><b>Unified MCP Tool Layer:</b> Single tool registry integrating live market data, company news, <b>SEC EDGAR filings</b>, and web search.</li>
        <li><b>Self-Correcting RAG:</b> Bounded critic-driven revision loop + TF-IDF/cosine-similarity retriever with source-attributed citations and checkpointing.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Python-stdlib_Graph-3776AB?style=flat-square&logo=python&logoColor=white"/>
        <img src="https://img.shields.io/badge/Architecture-MCP_%26_RAG-000000?style=flat-square"/>
        <img src="https://img.shields.io/badge/Agents-7_Nodes-2EA44F?style=flat-square"/>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>☁️ <a href="https://github.com/KDarshan-K">Secure AI Cloud RL Scheduler</a></h3>
      <p>Closed-loop Deep RL scheduler (PPO, DQN, DDPG) benchmarked on 100-host Google, Alibaba, and AWS workload traces in CloudSim Plus.</p>
      <ul>
        <li><b>Multi-Objective Optimization:</b> Balanced CPU, energy, SLA, cost, and host trust to reach <b>92% CPU utilization (+24 pts over FCFS)</b>.</li>
        <li><b>Real-Time Threat Response:</b> Redirected <b>96.4%</b> of sensitive workloads away from compromised hosts in <b>2.3s</b>; deployed via FastAPI + React.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/PyTorch-Deep_RL-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
        <img src="https://img.shields.io/badge/FastAPI-Inference-005571?style=flat-square&logo=fastapi"/>
        <img src="https://img.shields.io/badge/IEEE_TEMCAT-2026-F59E0B?style=flat-square"/>
      </p>
    </td>
  </tr>
  <tr>
    <td colspan="2" valign="top">
      <h3>🚚 <a href="https://github.com/KDarshan-K/Unified-logistics">Unified Global Logistics Hub</a></h3>
      <p>Full-stack logistics platform featuring sub-2ms geospatial querying and a natural-language Text-to-NoSQL admin query engine.</p>
      <ul>
        <li><b>Sub-2ms Document Model:</b> Engineered a MongoDB schema achieving <b>1.66ms average query latency</b> across single-document lookups and full collection fetches.</li>
        <li><b>Geospatial Dispatch & AI Admin:</b> Built nearest-driver assignment via MongoDB <code>$near</code> (10km radius, 3s live polling) and a <b>Groq (Llama 3.1)</b> admin panel that compiles plain-English questions into live MongoDB aggregation pipelines.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/FastAPI-005571?style=flat-square&logo=fastapi"/>
        <img src="https://img.shields.io/badge/MongoDB-1.66ms_Avg-4ea94b?style=flat-square&logo=mongodb&logoColor=white"/>
        <img src="https://img.shields.io/badge/Groq-Llama_3.1-F55036?style=flat-square"/>
        <img src="https://img.shields.io/badge/Jinja2-B41717?style=flat-square&logo=jinja&logoColor=white"/>
      </p>
    </td>
  </tr>
</table>

<details>
<summary><b>📐 View System Architecture & Benchmarks (7-Agent Graph + Deep RL Metrics)</b></summary>
<br/>

#### 1. Multi-Agent Financial Research Graph (`stdlib` Engine)
```mermaid
graph LR
    U[User Query] --> O[Orchestrator Agent]
    O --> M[Market Agent]
    O --> N[News Agent]
    O --> S[Search Agent]
    O --> R[RAG Retriever]
    
    subgraph Unified MCP Tool Layer
        T[(SEC EDGAR / Market / Web APIs)]
    end
    
    M & N & S & R <--> T
    M & N & S & R --> A[Analyst Agent]
    A --> C{Critic Agent}
    C -->|Revision Loop| A
    C -->|Approved + Citations| F[Final Report]
