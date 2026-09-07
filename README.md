<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&pause=1000&color=6C63FF&center=true&vCenter=true&width=600&lines=Hi%2C+I'm+Maia+Bazerji+%F0%9F%91%8B;AI+Engineer+%7C+RAG+%26+LLM+in+production;Evaluation%2C+tracing%2C+cost+and+latency." alt="Typing SVG" />
  <br/><br/>
  <a href="https://maiabazerji.com"><img src="https://img.shields.io/badge/Website-6C63FF?style=flat-square&logo=googlechrome&logoColor=white" alt="Website" /></a>
  <a href="https://www.linkedin.com/in/maiabazerji"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://medium.com/@maiabazerji"><img src="https://img.shields.io/badge/Medium-000000?style=flat-square&logo=medium&logoColor=white" alt="Medium" /></a>
  <a href="https://github.com/maiabazerji"><img src="https://img.shields.io/github/followers/maiabazerji?style=flat-square&color=6C63FF" alt="GitHub followers" /></a>
  <a href="https://github.com/maiabazerji"><img src="https://komarev.com/ghpvc/?username=maiabazerji&style=flat-square&color=6C63FF" alt="Profile views" /></a>
</div>

---

## About Me

AI Engineer with an M.Sc. in Artificial Intelligence and Data. I build retrieval-augmented generation (RAG) and large language model (LLM) systems that reach production.

For 16 months I was the sole engineer on an AI-driven data platform, owning it from ingestion to the front end. Query latency went from 10 seconds to 2 seconds across a catalogue of 100,000+ records. What I care about is what happens after the demo: evaluation, tracing model decisions, cost and latency. That is why I built EvalRAG.

- 📍 Paris / Île-de-France, France. Looking for a CDI as an **AI Engineer or Machine Learning Engineer**.
- ✍️ I write about applied machine learning and MLOps on [Medium](https://medium.com/@maiabazerji).
- 🇫🇷 🇬🇧 Bilingual French and English.

---

## Tech Stack

### Machine Learning & AI
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)

### Data & Engineering
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j-4581C3?style=flat-square&logo=neo4j&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)

### MLOps & Deployment
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![Langfuse](https://img.shields.io/badge/Langfuse-000000?style=flat-square&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white)

---

## Featured Projects

### 🔍 EvalRAG : RAG pipeline + evaluation framework
Open-source evaluation harness built to catch quality regressions before they ship, paired with a production RAG system.
- Benchmarks Classic, Graph and Agentic retrieval on the same corpus, measuring latency, token cost and answer quality.
- Hybrid retrieval (BM25 + dense), golden dataset design, faithfulness and relevance scoring, RAGAS integration.
- FastAPI backend, Qdrant vector store, React front end.
- *Keywords:* `RAG` `LLM Evaluation` `FastAPI` `Qdrant` `Python`

**[Repository](https://github.com/maiabazerji/evalrag) · [Write-up on Medium](https://medium.com/@maiabazerji)**

### 🗂️ Knowledge Management Platform (Kabeen)
Built solo as the sole engineer, from ingestion through to the front end.
- Extract-transform-load (ETL) pipeline, hybrid anomaly detector, RAG system and knowledge graph over a catalogue of 100,000+ applications.
- Query latency reduced from 10 seconds to 2 seconds, access extended from 10 analysts to more than 1,000 users.
- Zero-downtime deployment, model monitoring in service, human validation kept in the loop where accuracy mattered most.
- *Keywords:* `RAG` `Knowledge Graph` `ETL` `Anomaly Detection` `Production`

**[Case study](https://maiabazerji.com/projects/rag-kabeen/)**

### 🏷️ NER on French travel orders
Named entity recognition (NER) extracting structured entities from unstructured French administrative documents.
- Custom spaCy v3 pipeline benchmarked against a fine-tuned CamemBERT model, comparing accuracy against inference cost.
- BIO tagging and token classification, with custom augmentation to raise F1 on a low-resource dataset.
- Deployed extraction API plus a command-line interface for batch processing.
- *Keywords:* `NLP` `CamemBERT` `spaCy` `Token Classification` `PyTorch`

**[Repository](https://github.com/maiabazerji/Travel_order_NER)**

### 🧾 VIFACT : French e-invoicing compliance
Multi-agent platform for the French electronic invoicing mandate (Factur-X, QR, PDP standards).
- LLM-assisted data capture from invoice documents, with multi-role agent extraction and a human verification step.
- FastAPI backend, React front end, fully containerised with Docker.
- *Keywords:* `Multi-Agent` `LLM` `Document AI` `Factur-X` `FastAPI`

### 🛡️ On-device moderation service
Three-tier on-device architecture for real-time chat safety, where images never leave the device.
- MobileNetV2 → MobileNetV3 → ViT-Video escalation, tuned for edge deployment and minimal latency.
- *Keywords:* `Computer Vision` `Edge AI` `On-Device Inference`

**[Repository](https://github.com/maiabazerji/moderation-service)**

---

## Let's Connect

Open to discussing AI systems, retrieval architecture, or CDI opportunities in Paris / Île-de-France.

[![LinkedIn](https://img.shields.io/badge/Reach_out_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/maiabazerji)

---

<p align="center"><i>Portfolio and full CV at <a href="https://maiabazerji.com">maiabazerji.com</a></i></p>
