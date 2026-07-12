<h1 align="center">Aaditya Poonia</h1>

<p align="center">
  I build AI systems that <b>reason, retrieve, and act</b> —<br/>
  and I care as much about the guardrails as the demo.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/aaditya-poonia/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:aadityapoonia81@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://github.com/AadityaPoonia/Project-Portfolio"><img src="https://img.shields.io/badge/Portfolio-181717?style=for-the-badge&logo=github&logoColor=white" alt="Portfolio"/></a>
</p>

## About

I work where multi-agent orchestration, retrieval, and messy real-world data collide — turning "cool demo" into "thing you can actually ship." Three years of building data and AI systems that people rely on, from analytics dashboards to multi-agent platforms.

- 🔭 Currently focused on **agentic AI**: multi-agent systems with LangGraph, RAG over real-world documents, and multimodal document intelligence
- 🛡️ Obsessed with the unglamorous parts that make AI trustworthy — prompt-injection defence, least-privilege tools, sandboxed execution, eval harnesses, tool-call tracing
- 🎓 MSc Data Science, **University of Glasgow** — dissertation on fine-tuning LLMs to reason about legal judgments
- 💬 Open to conversations about AI engineering, applied ML, and anything where data meets judgment

## Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🤖 [Agentic Travel & Tourism AI Platform](https://github.com/AadityaPoonia/Project-Portfolio/tree/main/Agentic%20Travel%20AI%20Platform)

A supervisor routes each query to a specialist agent — SQL analytics, CSV analysis, live weather, budget math, or multimodal document Q&A.

Built like a product, not a demo: **read-only SQL** behind a database authorizer, **AST-validated pandas** under a timeout, **layered prompt-injection defence** with deterministic tests, and full tool-call + cost tracing in the UI.

`LangGraph` `LangChain` `FAISS` `Streamlit` `MongoDB`

</td>
<td width="50%" valign="top">

### 🛰️ [SanctiSight — See Risk Before It Strikes](https://github.com/AadityaPoonia/Project-Portfolio/tree/main/SanctiSight)

Semantically links entities in global news to sanctions lists — **flagging risky entities before they hit official watchlists**.

Embeds 90 days of GDELT news and cross-references OFAC/OpenSanctions via vector search, catching contextual relationships that keyword matching misses entirely.

`BigQuery ML` `Vertex AI` `Vector Search` `GDELT`

<sub>Google Cloud × Kaggle BigQuery AI Hackathon 2025</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ⚖️ [Legal Judgment Analysis with Fine-Tuned LLMs](https://github.com/AadityaPoonia/Project-Portfolio/tree/main/Legal%20Judgment%20Analysis%20LLM)

Fine-tuned **SaulLM-7B with LoRA** on Indian legal judgments, paired with FAISS precedent retrieval to auto-generate case analysis.

Key finding: retrieval-supplied context **beat legal-domain pretraining**. Evaluated with BERTScore/ROUGE/METEOR *and* a human legal team — because overlap metrics can't tell you if reasoning is correct.

`SaulLM-7B` `LoRA` `FAISS` `DSPy` `PyTorch`

<sub>MSc dissertation, University of Glasgow</sub>

</td>
<td width="50%" valign="top">

### 🔍 [RAG Pipeline with Reranking & Eval](https://github.com/AadityaPoonia/Project-Portfolio/tree/main/RAG%20Pipeline%20with%20Reranking%20%26%20Eval)

A RAG system with the parts most demos skip: **BM25 + Cross-Encoder + vector fusion** for reranking, an **"I don't know" policy** that refuses low-confidence answers, and a **hit@k evaluation harness**.

Degrades gracefully to fully-offline mode (TF-IDF + extractive answers) when no API key is present.

`Cross-Encoder` `BM25` `OpenAI` `Python`

</td>
</tr>
</table>

<p align="center">
  <a href="https://github.com/AadityaPoonia/Project-Portfolio"><b>→ Browse all projects</b></a>
</p>

## Toolkit

**AI & LLM Engineering**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langgraph&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white)

<sub>RAG · multi-agent orchestration · LoRA fine-tuning · DSPy · Sentence Transformers · prompt-injection mitigation · multimodal document intelligence (OCR, table extraction, vision captioning)</sub>

**Cloud**

![Google Cloud](https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-669DF6?style=flat-square&logo=googlebigquery&logoColor=white)
![Vertex AI](https://img.shields.io/badge/Vertex%20AI-4285F4?style=flat-square&logo=googlecloud&logoColor=white)

**Data & ML**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

**Apps & Visualization**

![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Looker Studio](https://img.shields.io/badge/Looker%20Studio-4285F4?style=flat-square&logo=looker&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white)
![Altair](https://img.shields.io/badge/Altair%20%2F%20Vega--Lite-3F4F75?style=flat-square&logo=plotly&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

<p align="center">
  <a href="https://www.linkedin.com/in/aaditya-poonia/">LinkedIn</a> ·
  <a href="mailto:aadityapoonia81@gmail.com">aadityapoonia81@gmail.com</a> ·
  <a href="https://github.com/AadityaPoonia/Project-Portfolio">Project Portfolio</a>
</p>
