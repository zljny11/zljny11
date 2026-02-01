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

### Languages
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![Lua](https://img.shields.io/badge/Lua-2C2D72?style=flat&logo=lua&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white)
![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

### Backend
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=flat&logo=apachekafka&logoColor=white)

### AI / RAG
![LangChain](https://img.shields.io/badge/LangChain-121212?style=flat)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6F00?style=flat)

### Engineering
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![JMeter](https://img.shields.io/badge/JMeter-D22128?style=flat)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat&logo=postman&logoColor=white)

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
