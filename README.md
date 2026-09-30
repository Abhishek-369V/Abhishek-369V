<div align="center">

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&pause=1200&color=4F8EF7&center=true&vCenter=true&width=850&lines=Hi%2C+I'm+Abhishek+%F0%9F%91%8B;AI+Engineer+(Agentic+AI+%2B+Gen+AI);Building+AI+that+solves+real+problems" alt="Typing SVG" />
</a>

<br/>

<p>
  <a href="https://www.linkedin.com/in/madanala-abhishek-varma/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:abhishekmadanala@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact-EA4335?style=flat-square&logo=gmail&logoColor=white" /></a>
  <img src="https://img.shields.io/badge/Open%20to-AI%20Engineering%20%7C%20GenAI%20%7C%20ML-brightgreen?style=flat" />
</p>

<b>Building AI systems from data → retrieval → reasoning → APIs → deployment.</b>

</div>

---

## About

I'm **Madanala Abhishek Varma**, a **B.Tech CSE graduate focused on AI engineering**, with hands-on experience across machine learning, data analytics, GenAI and agentic systems.

I started with frontend development, moved into machine learning and data pipelines, and gradually shifted toward building **AI applications that combine retrieval, stateful workflows, APIs, evaluation and deployment**.

I enjoy working across the full system rather than only the model layer.

<table>
<tr>
<td align="center" width="16%"><b>DATA</b></td>
<td align="center" width="16%"><b>ML</b></td>
<td align="center" width="16%"><b>RAG</b></td>
<td align="center" width="16%"><b>AGENTS</b></td>
<td align="center" width="16%"><b>APIs</b></td>
<td align="center" width="20%"><b>DEPLOYMENT</b></td>
</tr>
<tr>
<td align="center">Pipelines</td>
<td align="center">Models</td>
<td align="center">Retrieval</td>
<td align="center">Workflows</td>
<td align="center">Backend</td>
<td align="center">Cloud</td>
</tr>
</table>

---

## What I Build

<table>
<tr>
<td width="50%" valign="top">

### Agentic AI

Stateful AI workflows that coordinate retrieval, tools, reasoning and structured outputs.

`LangGraph` `LangChain` `RAG`

</td>
<td width="50%" valign="top">

### Multimodal AI

Applications that combine video, speech, text and visual information.

`Whisper` `AWS Rekognition` `LLMs`

</td>
</tr>

<tr>
<td width="50%" valign="top">

### ML Systems

End-to-end machine learning workflows from preprocessing to evaluation and inference.

`Scikit-learn` `XGBoost` `TensorFlow`

</td>
<td width="50%" valign="top">

### Data Systems

Data pipelines and analytical applications built around Python, SQL and databases.

`Pandas` `SQL` `SQLite` `Power BI`

</td>
</tr>
</table>

---

# Featured Projects

## 01 · Brand Guardian AI

### Multimodal Video Compliance Auditor

An agentic system designed to audit video content against retrieved advertising and compliance policies.

```text
                    VIDEO
                      │
             ┌────────┴────────┐
             ▼                 ▼
          SPEECH         ON-SCREEN TEXT
             │                 │
          Whisper        AWS Rekognition
             │                 │
             └────────┬────────┘
                      ▼
               POLICY RETRIEVAL
              FAISS + Embeddings
                      │
                      ▼
              LANGGRAPH WORKFLOW
                      │
                      ▼
                   GROQ LLM
                      │
                      ▼
             PASS / FAIL + FINDINGS
                      │
                      ▼
               LANGSMITH TRACE
```

**Stack**

`LangGraph` `RAG` `Whisper` `AWS Rekognition` `RAGAS` <br>
`FAISS` `Sentence Transformers` `Groq` `FastAPI` `Docker` `LangSmith`

**Highlights**

- Multimodal speech and on-screen text extraction
- Retrieval-grounded compliance reasoning
- Stateful LangGraph orchestration
- Structured findings and severity classification
- Automated testing and RAG evaluation
- LangSmith tracing and performance analysis

**[Repository](https://github.com/Abhishek-369V/brand-guardian-ai)** · **[Demo](https://youtu.be/1xkJx8qgp2o)**

---

## 02 · Nifty 100 Financial Intelligence

### End-to-End Financial Analytics Platform

A financial intelligence platform covering **92 Nifty 100 companies**, combining ETL, financial analytics, screening, peer benchmarking, ML-based analysis and reporting.

```text
              12 SOURCE DATASETS
                      │
                      ▼
               ETL + VALIDATION
                      │
                      ▼
                SQLITE DATA LAYER
                      │
                 ┌────┼─────┬──────────┐
                 ▼    ▼     ▼          ▼
                KPI  SCREEN  PEERS    ML/NLP
                 │    │     │          │
                 └────┴─────┴──────────┘
                            │
                            ▼
                     FASTAPI + STREAMLIT
                            │
                            ▼
                      FINANCIAL REPORTS
```

**Stack**

`Python` `Pandas` `SQL` `SQLite` `FastAPI` <br>
`financial-analysis` `Streamlit` `Scikit-learn` `KMeans` 

**Highlights**

- 12-source ETL pipeline with data-quality validation
- 30+ financial metrics
- 6 preset screeners
- 11 peer groups for benchmarking
- KMeans-based analytical clustering
- 19-endpoint FastAPI backend
- 8-screen Streamlit dashboard
- 172 automated tests
- Automated company, sector and portfolio reports

**[Repository](https://github.com/Abhishek-369V/N100-financial-intelligence-platform)** · **[Live](https://nifty100-finintel.streamlit.app/)**

---

## 03 · ArXiv Agentic RAG

### Research Assistant with Retrieval Evaluation

An agentic research system designed to search and reason over **ArXiv research papers** using Agentic RAG, with **Exa Web Search as a fallback when local retrieval is insufficient**.

```text
                  USER QUERY
                      │
                      ▼
                QUERY ANALYSIS
                      │
                      ▼
             LOCAL ARXIV RETRIEVAL
                      │
                      ▼
             RETRIEVAL EVALUATION
                      │
          ┌───────────┴───────────┐
          │                       │
     SUFFICIENT              INSUFFICIENT
          │                       │
          │                       ▼
          │                EXA WEB SEARCH
          │                       │
          └───────────┬───────────┘
                      ▼
                CONTEXT ASSEMBLY
                      │
                      ▼
                LLM REASONING
                      │
                      ▼
              GROUNDED RESPONSE
```

**Stack**

`LangGraph` `LangChain` `ChromaDB` `OpenAI Embeddings`  <br>
`Retrieval Evaluation` `Exa-api` `LLMs` `OpenAI API`

**Key Engineering Work**

- Retrieves relevant research content from the local ArXiv knowledge base
- Evaluates retrieved context before generating an answer
- Uses **Exa Web Search as a fallback** when local retrieval is insufficient
- Combines retrieved evidence before LLM-based reasoning
- Uses an agentic workflow to decide when additional search is required
- Focuses on retrieval quality and grounded responses rather than relying only on the LLM

**[Repository](https://github.com/Abhishek-369V/arxiv-agentic-rag)** · **[Demo](https://www.loom.com/share/29e548f5cad94e5795b211e235ce07ba)**

---

## 04 · Mutual Fund Analytics Platform

### Financial Data Engineering + Risk Analytics

An end-to-end mutual fund analytics platform developed during my Data Analyst internship, processing 87K+ AMFI India records across 40 fund schemes via data ingestion, ETL, database modeling, exploratory analysis, performance analytics, risk analysis and Power BI reporting.

  ```text
              RAW FINANCIAL DATA
                     │
                     ▼
             DATA INGESTION
                     │
                     ▼
           CLEANING + TRANSFORMATION
                     │
                     ▼
            SQLITE STAR SCHEMA
                     │
                ┌────┼─────────┐
                ▼    ▼         ▼
               EDA  PERFORMANCE  RISK
                    ANALYTICS    ANALYTICS
                │       │          │
                └───────┴──────────┘
                        │
                        ▼
                POWER BI DASHBOARD
```

**Stack**

`Python` `Pandas` `Numpy` `SQL` `SQLite` <br>
`Data visualization` `plotly` `Power BI`

**Analytics**

`CAGR` `Sharpe` `Sortino` `Alpha` `Beta`  
`Maximum Drawdown` `VaR` `CVaR` `HHI`

**Key Engineering Work**

- Built ETL workflows for mutual fund datasets
- Cleaned and transformed NAV, transaction, AUM and SIP data
- Designed a SQLite star schema for analytical workloads
- Implemented performance and risk-adjusted financial metrics
- Developed analytical SQL queries for fund and investor analysis
- Built a risk-based fund recommender
- Created a 4-page interactive Power BI dashboard with drill-through and slicers

**[Repository](https://github.com/Abhishek-369V/MF_Analytics_Platform) · [Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiYTMzMWEwNjctNjcyMy00MWY1LThiNzAtN2I3NmM0NzMzZGJkIiwidCI6ImMxMTBiOWNmLTFmOGMtNDVhMS1iMmJlLWI0ZGNkNGU0NjE1MSJ9)**

---

# Technical Stack

### AI / GenAI

`LangGraph` `LangChain` `CrewAI` `Autogen` `RAG` `FAISS`  <br>
`Sentence Transformers` `OpenAI` `Gemini` `Groq` `Hugging Face`

### Machine Learning

`Python` `Scikit-learn` `XGBoost` `Random Forest` <br>
`TensorFlow` `NLP` `Classification` `Regression` `KMeans`

### Data & Analytics

`Pandas` `NumPy` `SQL` `SQLite` `PostgreSQL`  <br>
`Matplotlib` `Seaborn` `ETL` `Power BI` `Streamlit`

### Full-Stack Python & Cloud

`FastAPI` `REST APIs` `Docker` `Git` `GitHub` <br>
`AWS` `Azure` `Streamlit` `React` `JavaScript` `Tailwind CSS`

---

# My Journey: From Data to AI Systems

```text
React
  │
  ▼
Machine Learning
  │
  ▼
NLP + Data Analytics
  │
  ▼
Data Pipelines + SQL
  │
  ▼
GenAI + RAG
  │
  ▼
Agentic AI
  │
  ▼
End-to-End AI Systems
```

The common thread:

> **Understand the problem → build the pipeline → connect the components → evaluate the system → deploy it.**

---

# Currently Focused On

<table>
<tr>
<td width="50%" valign="top">

### AI

- Agentic AI
- GenAI applications
- Advanced RAG
- Retrieval evaluation
- Multimodal AI

</td>
<td width="50%" valign="top">

### Engineering

- FastAPI
- AI backend systems
- Data pipelines
- Docker
- Cloud deployment
- Observability

</td>
</tr>
</table>

---

# Experience

| Role | Focus |
|---|---|
| **Data Analyst Intern · Bluestock Fintech** | Financial analytics · ETL · SQL · Risk metrics · Power BI |
| **Frontend Developer Intern · Coreline Solutions** | React · Tailwind CSS · AI API integration · Voice interfaces |
| **AI/ML Intern · Edunet Foundation** | NLP · TF-IDF · Random Forest · Gradient Boosting |

---

# Connect

I'm interested in opportunities involving:

**AI Engineering · Agentic AI · GenAI · Machine Learning · Data/ML Systems**

<div align="center">

<a href="https://www.linkedin.com/in/madanala-abhishek-varma/">
<img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
&nbsp;
<a href="mailto:abhishekmadanala@gmail.com">
<img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
&nbsp;
<a href="https://github.com/Abhishek-369V?tab=repositories">
<img src="https://img.shields.io/badge/GitHub-Explore-181717?style=for-the-badge&logo=github&logoColor=white" /></a>

<br/>
<br/>

<b>DATA → RETRIEVAL → REASONING → SYSTEMS → DEPLOYMENT</b>

<br/>

<i>Building things, breaking things, understanding why, and building them better.</i>

</div>
