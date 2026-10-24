# Muhammad Aitessam Ahmed

**Senior AI/ML Engineer** · LLMs, RAG and agentic systems for regulated industries (healthcare, fintech, defence)

5+ years taking AI from raw data to production systems that real users depend on: clinical
document pipelines feeding hospital EHRs, physician-facing medical assistants, radiology
inference services and edge computer vision on drones.

📍 Islamabad, Pakistan (UTC+5) · Open to relocation to **Saudi Arabia and the wider Gulf**, and to
**remote roles with EU/UK teams**

[LinkedIn](https://www.linkedin.com/in/muhammad-aitessam-ahmed-18a815113) ·
[Portfolio](https://aitessam.github.io) ·
[Email](mailto:aitessam@gmail.com)

---

## Selected impact

Most of my production work lives in employers' private repositories. Highlights:

- **Healthcare AI (current role):** built the AI layer of a live enterprise healthcare product.
  - A document pipeline (OCR plus LLM entity extraction) that outputs validated FHIR R4 resources into the hospital EHR, cutting manual data entry by **60 to 70%**.
  - Dictation to structured SOAP notes, cutting physician documentation time by about **50%**.
  - A RAG medical assistant for clinicians, with PHI isolation, audit logging and output guardrails.
- **Medical imaging:** a lung nodule classification service (CNN inference plus LLM-written reports, GPU-served FastAPI) in a live radiology workflow, cutting review effort by about **40%**.
- **Production ML at scale:** three AI backends on AWS (generative watermark removal, virtual try-on, image automation) with GPU serving, CI/CD and zero-downtime deploys. Also an image-intelligence platform processing thousands of items a day.
- **Defence research:** an LSTM fault-detection system on multi-sensor UAV telemetry that improved autonomous system reliability by **25%**.
- **Edge AI:** a YOLO human-detection model running on drones at under **200 ms** per frame with no cloud, plus a multi-UAV search-and-rescue system.

## Featured projects

| Project | What it shows |
|---|---|
| [**MedRAG**](https://github.com/aitessam/MedRAG) | A medical assistant that answers questions from the patient's own record: hybrid search, cross-encoder reranking, voice, privacy-safe logging. Its evaluation report shows how measurement exposed a design flaw (the original gate would have refused 61% of answerable questions) and how it was fixed. 106 tests, CI, Docker. |
| [**DocScribe**](https://github.com/aitessam/doc_scribe) | Live transcription of doctor-patient consultations in mixed Urdu and English, turned into a structured clinical note by a local (Ollama) or cloud LLM. Streaming speech-to-text, correct right-to-left Urdu rendering, and retries with typed errors from microphone to API. FastAPI and Streamlit, 29 tests, CI, Docker. |
| [**Fintech-Agent-Arabic**](https://github.com/aitessam/Fintech-Agent-Arabic) | A LangGraph agent for Arabic and English financial documents (bank statements, KYC, loan forms). Entity extraction, calculations, SAMA-oriented compliance checks and a hash-chained audit trail. |
| [**ARABERT_RAG**](https://github.com/aitessam/ARABERT_RAG) | RAG over Arabic PDFs with page-level citations. Handles right-to-left extraction, Arabic normalisation and mixed-script search. |
| [**bilingual-clinical-rag**](https://github.com/aitessam/bilingual-clinical-rag) | English/Arabic clinical question answering with fused BM25 and dense retrieval, reranking, a LangGraph agent and RAGAS evaluation. |

## Tech I work with

- **AI/ML:** LLMs, RAG (BM25, vector search, cross-encoder reranking), agents (LangGraph, CrewAI, MCP), NLP and clinical NLP, computer vision, fine-tuning, PyTorch, TensorFlow, Hugging Face
- **Serving and MLOps:** FastAPI, async Python, Docker, Kubernetes, CI/CD, GPU inference, AWS, Azure
- **Data:** FAISS, Pinecone, Chroma, Weaviate, PostgreSQL, MongoDB, Elasticsearch, Kafka
- **Domains:** FHIR R4 and EHR integration, Arabic NLP, regulated and audit-heavy environments

## Recognition

- 🥇 **1st place**, International Free Mission UAV Competition, Teknofest 2021, Istanbul (team captain; teams from 30+ countries)
- 📄 **IEEE publication:** "Design and Development of Audio Processing and Speech Recognition Algorithm", ICASE 2021 ([DOI](https://doi.org/10.1109/ICASE54940.2021.9904277))
- 🎓 BSc Engineering, Institute of Space Technology, Islamabad
