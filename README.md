<h1 align="center">Aaditya Poonia</h1>

<p align="center">
  <b>Senior AI Engineer</b> &nbsp;·&nbsp; MSc Data Science &nbsp;·&nbsp; Glasgow, UK
</p>

<p align="center">
  I build agentic AI systems that use the right tool at the right time —<br/>
  and I care as much about the guardrails as the demo.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/aaditya-poonia/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:aadityapoonia81@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://github.com/AadityaPoonia/Project-Portfolio"><img src="https://img.shields.io/badge/Portfolio-181717?style=for-the-badge&logo=github&logoColor=white" alt="Portfolio"/></a>
</p>

---

## About

Three years of turning messy business data into working systems — insight, dashboards, ML workflows, and AI applications that people actually use.

My current focus is **agentic AI**: multi-agent orchestration, retrieval-augmented generation, and multimodal document intelligence. What interests me most is the gap between an AI demo and an AI product — the routing that has to be cheap and correct, the SQL that has to be read-only, the retrieved context that must never be trusted as an instruction. That gap is where the engineering lives.

- 🔭 Building multi-agent systems with **LangGraph**, RAG pipelines over messy real-world documents, and data apps that make analysis easy for non-technical users
- 🛡️ Especially interested in **AI safety in practice** — prompt-injection mitigation, least-privilege tools, sandboxed execution, and tool-call tracing
- 🎓 MSc Data Science, **University of Glasgow** — dissertation on legal judgment analysis with fine-tuned LLMs
- 💬 Open to **AI engineering, applied ML, and data science** opportunities

---

## Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🤖 [Agentic Travel & Tourism AI Platform](https://github.com/AadityaPoonia/Project-Portfolio/tree/main/Agentic%20Travel%20AI%20Platform)

A multi-agent assistant that routes each query to a specialist agent — SQL analytics, CSV analysis, live weather, budget estimation, or document Q&A.

Built like a product, not a demo: **read-only SQL** behind a database authorizer, **AST-validated pandas** execution under a timeout, **layered prompt-injection defence** with deterministic tests, plus token/cost tracking and full tool-call tracing in the UI.

`LangGraph` `LangChain` `FAISS` `Streamlit` `MongoDB`

</td>
<td width="50%" valign="top">

### 🛰️ [SanctiSight — See Risk Before It Strikes](https://github.com/AadityaPoonia/Project-Portfolio/tree/main/SanctiSight)

Risk-intelligence pipeline that semantically links entities in global news to sanctions lists — **spotting risky entities before they hit official watchlists**.

Embeds 90 days of GDELT news and cross-references OFAC/OpenSanctions via vector search, catching contextual relationships that keyword matching misses entirely.

`BigQuery ML` `Vertex AI` `Vector Search` `GDELT`

<sub>Google Cloud × Kaggle BigQuery AI Hackathon 2025</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ⚖️ [Legal Judgment Analysis with Fine-Tuned LLMs](https://github.com/AadityaPoonia/Project-Portfolio/tree/main/Legal%20Judgment%20Analysis%20LLM)

MSc dissertation. Fine-tuned **SaulLM-7B with LoRA** on Indian legal judgments and paired it with FAISS precedent retrieval to auto-generate case analysis.

Retrieval-supplied context turned out to beat legal-domain pretraining — evaluated with BERTScore/ROUGE/METEOR *and* a human legal team, because overlap metrics can't tell you if reasoning is correct.

`SaulLM-7B` `LoRA` `FAISS` `DSPy` `PyTorch`

</td>
<td width="50%" valign="top">

### 🔍 [RAG Pipeline with Reranking & Eval](https://github.com/AadityaPoonia/Project-Portfolio/tree/main/RAG%20Pipeline%20with%20Reranking%20%26%20Eval)

A RAG system with the parts most demos skip: **BM25 + Cross-Encoder + vector fusion** for reranking, an **"I don't know" policy** that refuses low-confidence answers, and a **hit@k evaluation harness**.

Runs fully offline with TF-IDF embeddings and extractive generation when no API key is present.

`Cross-Encoder` `BM25` `OpenAI` `Python`

</td>
</tr>
</table>

<p align="center">
  <a href="https://github.com/AadityaPoonia/Project-Portfolio"><b>→ Browse all projects</b></a>
</p>

---

## Toolkit

**AI & LLM Engineering**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langgraph&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white)

<sub>RAG · Multi-agent orchestration · LoRA fine-tuning · DSPy · Sentence Transformers · Prompt-injection mitigation · Multimodal document intelligence (OCR, table extraction, vision captioning)</sub>

**Data & ML**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)

**Data Platform & Apps**

![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-669DF6?style=flat-square&logo=googlebigquery&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

**Visualization**

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white)
![Plotly](https://img.shields.io/badge/Altair%20%2F%20Vega--Lite-3F4F75?style=flat-square&logo=plotly&logoColor=white)

---

## GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=AadityaPoonia&show_icons=true&hide_border=true&title_color=0A66C2&icon_color=0A66C2&count_private=true" alt="GitHub stats"/>
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=AadityaPoonia&layout=compact&hide_border=true&title_color=0A66C2&langs_count=6" alt="Top languages"/>
</p>

---

<p align="center">
  <sub>Open to data science, analytics, AI engineering, and applied machine learning opportunities.</sub>
</p>
