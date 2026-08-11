<h1 align="center">ice1x</h1>
<h3 align="center">Senior Data Platform Engineer | Remote</h3>

<p align="center">
  20+ years in software engineering. Building scalable backends, data platforms, and AI/RAG systems.
</p>

---

### Experience

- **Senior Platform Engineer** · Cloud Integration & Automation
- **Senior Data Platform Engineer**
  - **Research Platform** — low-code/no-code data platform on KubeFlow; added HPC execution so pipeline steps run on remote clusters, pluggable S3 external file storage, a web-VSCode editor running in the user's pod for editing pipeline steps, CSV import/export for the ClickHouse tabular-data integration, and a backend microservice converting client molecule files into the format the platform's molecule-rendering frontend needs
  - **RAG Knowledge Center** — bm25 highlights: new indexers, result post-processing, a chunk-with-highlights concatenation algorithm, minor bug fixes
  - separately, for a different division (a few months, unrelated to the platform work above) — Salesforce data pipelines (Kubernetes jobs, Python, Kafka) for Acronis / Constructor Learning Platform (LMS)
- **Data Platform Engineer** · Predictive Monitoring & Maintenance (PMM), industrial clients — IoT monitoring, telemetry caching, BI reporting; Argo Workflows and Kafka/Faust applications for aerophoto recognition pre-/post-processing

Earlier:

- **OSINT Data Pipelines** — automated collection across Bankruptcy, Law Courts, Tenders; name-parsing autocomplete with prefix trie
- **QA & Automation** — 11 years of test automation at Parallels (desktop & server virtualization), embedded systems at Stoneridge

---

### Tech Stack

| Category | Technologies |
|---|---|
| **Languages** | Python, SQL |
| **Backend** | FastAPI, Django/DRF, SQLAlchemy, aiohttp, Celery, Faust |
| **AI / RAG** | LangChain, LangFuse, Milvus, Qdrant, BERT, NLP (Natasha, Tomita, NLTK) |
| **Knowledge Graphs** | Memgraph, Neo4j, NebulaGraph, graph modeling, graph-based RAG, MCP servers |
| **SQL Databases** | PostgreSQL, ClickHouse |
| **NoSQL** | Redis, Elasticsearch |
| **Messaging** | Kafka, RabbitMQ |
| **Cloud** | AWS, Azure, GCP |
| **Infrastructure** | Kubernetes, KubeFlow, Docker, Jenkins, S3 |
| **Also working with** | Go, Rust (with AI coding assistants) |

---

### Featured Projects

| Project | Description | Tech |
|---|---|---|
| [DNA_RAG](https://github.com/ice1x/DNA_RAG) | LLM pipeline for analysing personal DNA data (23andMe, AncestryDNA, VCF) | Python |
| [century_of_war](https://github.com/ice1x/century_of_war) | Interactive timeline of 1,000+ military conflicts (1900–present) | Python |
| [shiva](https://github.com/ice1x/shiva) | Agentic PR code-review bot — n8n workflow that fetches the diff and reviews it with an LLM across configurable categories | Python |
| [drevo](https://github.com/ice1x/drevo) · [Docker image](https://hub.docker.com/r/ice1x/drevo) | Embedded graph + vector database in Rust, exposed over MCP as long-term memory for AI agents — Neo4j-compatible Bolt/Cypher, BM25 full-text & HNSW/semantic search; C-FFI/WASM/Python bindings | Rust |
| [drevo-mcp](https://github.com/ice1x/drevo-mcp) | FastMCP server exposing the drevo graph database to AI clients (Claude, Cline, OpenCode) as MCP tools — graph traversal, full-text search, node inspection | Python |
| [football-api-mcp](https://github.com/ice1x/football-api-mcp) | MCP Server for football-data.org API | Python |
| [neo4j-mcp](https://github.com/ice1x/neo4j-mcp) | MCP Server for Neo4j graph database | Python |
| [SoundForge](https://github.com/ice1x/SoundForge) | Native audio editor for Apple Silicon | Rust |
| [Axum_DAG_Manager](https://github.com/ice1x/Axum_DAG_Manager) | DAG workflow manager | Rust |
| [Django_DAG_manager](https://github.com/ice1x/Django_DAG_manager) | DAG workflow manager | Python |
| [autocomplete-full-name](https://github.com/ice1x/autocomplete-full-name) | Name parsing & autocomplete service | Python |
| [prefix_tree](https://github.com/ice1x/prefix_tree) | Prefix tree data structure | Python |
| [go-prefix-trie](https://github.com/ice1x/go-prefix-trie) | Prefix Trie implementation | Go |
| [rust_prefix_tree](https://github.com/ice1x/rust_prefix_tree) | Prefix tree data structure | Rust |
| [XYZ-to-MOL2-converter](https://github.com/ice1x/XYZ-to-MOL2-converter) | Chemical molecule file format converter | Python |
| [shqaff](https://github.com/ice1x/shqaff) | Database-backed task queue | Python |
| [fastapi_keycloak](https://github.com/ice1x/fastapi_keycloak) | FastAPI with Keycloak auth | Python |
| [smrouter](https://github.com/ice1x/smrouter) | Mirror YouTube live/upcoming broadcasts to Telegram channels | Python |

---

### Certifications

- AI with Knowledge Graphs: RAG System Mastery
- Databricks Certified Data Engineer Associate — Preparation
- Natural Language Processing with Classification and Vector Spaces (DeepLearning.AI)
- CKA (Certified Kubernetes Administrator) — in progress

