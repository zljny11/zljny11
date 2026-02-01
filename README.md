# Hi, I'm Ma Shunliang👋

I’m an undergraduate at NTUSG🇸🇬, **B.Sc. in Mathematical & Computer Sciences**, mainly working on **backend systems** and **applied AI Engineering**.

Before that, I spent my high school time in No.2 High School Affiliated to ECNU, Shanghai🇨🇳.

---

## What I’m working on

Lately, I’ve been spending most of my time on:

- Backend systems with **high concurrency and strict correctness requirements**
- Load-aware execution and **thread pool scheduling**
- Retrieval-Augmented Generation (RAG) systems with **explicit evaluation and controllable retrieval**
- Cross-language microservices (Java ↔ Python)

---

## Selected work

A few projects that represent how I approach engineering problems:

### UniTicket — campus ticketing system
A high-concurrency registration system designed for flash-sale–like workloads.

- Lock-free inventory control using Redis Lua scripts  
- Multi-level caching with logical expiration and delayed double deletion  
- Token bucket + sliding window rate limiting at API / user / IP levels  
- Asynchronous order and inventory consistency via Kafka  
- Stress-tested under constrained Docker resources with stable throughput

---

### LAS-Executor — load-adaptive task executor
A custom execution framework built on top of Java thread pools to handle mixed workloads.

- Dual feedback signals from CPU load and thread pool pressure  
- EWMA-based load smoothing and slope-triggered emergency mode  
- Pre-emptive thread expansion to avoid queue avalanches  
- Adaptive queuing strategies with blocking and backoff  
- Significantly reduced task drop rate under burst traffic

---

### CampusRAG-Engine — modular RAG service
A domain-specific RAG system for campus knowledge and long-context queries.

- Isolated LLM reasoning in a FastAPI service to avoid blocking upstream Java threads  
- Hybrid RAG pipeline with local embeddings and cloud-based reasoning  
- Retrieval logic refactored using LCEL for explicit context control  
- Faithfulness improved from 0.62 to 0.81 under RAGAS evaluation  
- Sub-100ms semantic search latency with FAISS indexing

---

## Tools I use a lot

- **Languages**: Java, Python, SQL, Lua  
- **Backend**: Spring Boot, FastAPI, Redis, Kafka  
- **AI / RAG**: LangChain, FAISS, Ollama  
- **Engineering**: Docker, Linux, Git, JMeter

---

## Outside of code

- 🎾 Tennis (around 3.0 level)  
- 🎸 Electric guitar (semi-professional)  
  - Some recordings and performances here:  
    https://space.bilibili.com/436709885?spm_id_from=333.788.0.0

---

## Contact

- Email: M240051@e.ntu.edu.sg  
- WeChat：zljny11
