

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=4DA8F7&center=true&vCenter=true&multiline=true&width=435&lines=Hi%2C+I'm+Darshan)](https://git.io/typing-svg)




A CS student focused on backend services, data-driven applications, and machine learning experiments. This README is my GitHub profile overview — it highlights my socials, tech stack, and GitHub activity.



## 📊 GitHub Stats:

<!-- GitHub Readme Stats: replace username value with your GitHub username -->


![GitHub Streak](https://streak-stats.demolab.com/?user=KDarshan-K&theme=gotham&hide_border=false)

[![Darshan's github activity graph](https://github-readme-activity-graph.vercel.app/graph?username=KDarshan-K&theme=xcode)](https://github.com/KDarshan-K/github-readme-activity-graph)



## 🌐 Socials:

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/darshankagadal/)

[![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:darshank2777@gmail.com)



# 💻 Tech Stack:
I work with a variety of languages, frameworks, and tools. Badges below are for quick recognition — see Projects for concrete examples.
- Languages:
  - C, C++, Python, SQL, Bash
  - ![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white) ![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white) ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Bash](https://img.shields.io/badge/GNU_Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
- Frameworks / Web:
  - Streamlit, FastAPI, Jinja2
  - ![Streamlit](https://img.shields.io/badge/Streamlit-%23FE4B4B.svg?style=for-the-badge&logo=streamlit&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)  ![Jinja](https://img.shields.io/badge/Jinja-B41717?style=for-the-badge&logo=jinja&logoColor=white)
- Databases:
  - MongoDB, MySQL, FAISS, ChromaDB
  - ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)
  - *(FAISS, ChromaDB — no official shield logos available)*
- Machine Learning / Data:
  - NumPy, Pandas, Matplotlib, scikit-learn, PyTorch, Seaborn, XGBoost
  - ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black) ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=pytorch&logoColor=white)
  - *(Seaborn, XGBoost — no official shield logos available)*
- Cloud & DevOps:
  - OCI, Docker, Linux
  - ![Docker](https://img.shields.io/badge/Docker-%232496ED.svg?style=for-the-badge&logo=docker&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black) ![Oracle](https://img.shields.io/badge/Oracle_Cloud-F80000?style=for-the-badge&logo=oracle&logoColor=white)
- Other tools:
  - Git, GitHub, Postman, Power BI
  - ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white) ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)  ![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

## 🚀 Projects

### 🔎 [FinRAG](https://github.com/KDarshan-K/FinRAG-boxbox)
AI-powered Finance RAG system for querying financial reports (10-Ks, earnings calls) in plain English.
- Document ingestion pipeline that extracts, cleans, and semantically chunks unstructured financial filings
- FAISS vector database for high-dimensional embedding storage and ultra-fast similarity search
- Live RAG pipeline connecting the vector store to a Groq LLM for grounded, retrieval-based answers
- **Stack:** Python · LangChain · FAISS · Groq · PyMuPDF

### 📈 [ForexTrendML](https://github.com/KDarshan-K/ForexTrendML-Boxbox)
End-to-end ML pipeline forecasting USD/INR exchange rate direction using market + macroeconomic data.
- Automated ingestion of real-time market data and asynchronous macro indicators via REST APIs (FRED, Yahoo Finance)
- ETL layer handling mismatched time-series frequencies — forward-fills and scaling to merge daily FX prices with monthly economic reports
- Modular 4-layer architecture separating ingestion, feature engineering, and modeling for scalability
- **Stack:** Python · Pandas · REST APIs · ETL

### 🚚 [Unified Global Logistics Hub](https://github.com/KDarshan-K/Unified-logistics)
Full-stack logistics platform with real-time tracking and an AI-powered admin query panel.
- MongoDB document model achieving sub-2ms query latency (1.66ms avg) for lookups and full collection fetches
- Geo-based nearest-driver assignment using MongoDB `$near` with a 10km radius, plus live 3-second status polling
- AI admin panel (Groq/Llama 3.1) that converts plain-English questions into executable MongoDB aggregation pipelines
- **Stack:** FastAPI · MongoDB · Groq · Jinja2 · Postman  
