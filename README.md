# Hi, I'm Ashish Kumar 👋

**Senior Software Engineer · Generative AI · Machine Learning**<br>
Bengaluru, India · open to AI/ML engineering roles in Dubai / UAE

I build backend systems and LLM applications in Python: agentic RAG, multi-agent workflows,
retrieval pipelines and the evaluation that proves they work. Before GenAI I spent five years
training and shipping computer-vision models and AWS microservices.

- 🏦 **Now:** Senior Associate Technology L2 at Publicis Sapient (client: Bank of America), agentic RAG with LangGraph and MCP
- 💳 **Before:** SDE III at JPMorgan Chase, concurrent compute-allocation services in Python
- 🚗 **Before that:** Senior Research Engineer at Netradyne for 5 years, driver-monitoring CNNs (seatbelt detection, precision 87% → 95% at 90% recall) and AWS video pipelines
- 🎓 M.Tech, IISc Bangalore (AI/ML minor) · GATE 2018 AIR 483

---

## ⭐ Featured project

### [Autonomous Financial Analyst & Auditor](https://github.com/ashishgenai2731/enterprise_doc_intelligence)

A multi-agent system that answers financial questions over SEC 10-K filings. One agent retrieves,
one runs Python in a sandbox for the arithmetic, and an auditor checks that every figure is backed
by a source.

| | |
|---|---|
| **Data** | 89 10-K filings from 30 companies, pulled from SEC EDGAR: 5.2M words, 98,137 indexed chunks |
| **Retrieval** | Pinecone dense + BM25 sparse, Reciprocal Rank Fusion, BGE cross-encoder reranker, company/year metadata filters |
| **Agents** | LangGraph state machine: RAG analyst → code executor (MCP sandbox) → compliance auditor, with up to 3 self-correction rounds |
| **Evaluation** | 1,074 test questions generated automatically from the companies' own XBRL data; every step's timing and score is [documented](https://github.com/ashishgenai2731/enterprise_doc_intelligence/blob/main/docs/PROJECT_METRICS.md) |
| **Serving** | FastAPI with Server-Sent Events streaming, Docker, local Mistral-7B via Ollama |

`LangGraph` `LangChain` `MCP` `Pinecone` `BM25` `FastAPI` `Ollama` `Pytest` `Docker`

---

## 🛠️ Tech I work with

- **GenAI / LLMs:** LangGraph · LangChain · LlamaIndex · RAG / agentic RAG · MCP · QLoRA / PEFT · LangSmith · RAGAs
- **Retrieval:** Pinecone · FAISS · Chroma · Qdrant · BM25 · cross-encoder reranking · Sentence-Transformers
- **ML / CV:** PyTorch · Transformers · OpenCV · CNNs / ResNet / YOLO · MLflow
- **Backend:** Python (asyncio, multiprocessing) · FastAPI · Flask · Redis · PostgreSQL · MongoDB
- **Cloud & DevOps:** AWS (Lambda, S3, EC2, SQS, CloudWatch, SageMaker) · Docker · Kubernetes · CI/CD

---

## 📫 Contact

[LinkedIn](https://www.linkedin.com/in/ashishkumar2712/)
