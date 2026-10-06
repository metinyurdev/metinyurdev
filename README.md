### Hi there, I'm Metin Yurduseven! 👋

🚀 **AI & Software Engineer**  
🔬 Specializing in **Agentic RAG, Multi-Stage LLM Fine-Tuning (PEFT/LoRA), and Full-Stack AI Product Architectures**  
💡 Bridging high-accuracy generative AI research with scalable, production-ready enterprise software systems  

---

## 🧠 About Me

- 🎓 **Background:** Computer Engineering graduate focused on building robust, end-to-end AI applications, enterprise-grade RAG frameworks, and domain-adapted LLMs.
- 🔬 **Fine-Tuning & LLMOps:** Experienced in training and aligning open-source LLMs (Qwen2.5-14B) across multi-phase curricula (Domain Adaptation ➔ Clinical Reasoning ➔ Ethical Guardrails) via Unsloth & PEFT/LoRA, benchmarking with **LLM-as-a-Judge** and **BERTScore/DeBERTa-v3**.
- ⚡ **Agentic & Hybrid RAG:** Architecting high-precision retrieval engines pairing dense semantic vector search (**Qdrant, FAISS**) with sparse retrieval (**BM25**), reranking (**bge-reranker**), dynamic query transformation, and hierarchical multi-agent orchestration.
- 💻 **Full-Stack Engineering:** Designing high-throughput, asynchronous backends with **Python & FastAPI**, crafting reactive modern UIs with **React, Vite & Tailwind CSS**, and orchestrating multi-container services with **Docker Compose**.
- ✍️ **Technical Writing:** Publishing in-depth technical blogs on **HackerNoon** deconstructing RAG mechanics, retrieval-generation dynamics, and advanced LLM systems.

---

## 🚀 Tech Stack

### 🧠 AI, LLMs & Retrieval Frameworks:
![LlamaIndex](https://img.shields.io/badge/LlamaIndex-1C3C3C?style=for-the-badge&logo=llamaindex&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/HuggingFace-FFCC00?style=for-the-badge&logo=huggingface&logoColor=black)
![Unsloth](https://img.shields.io/badge/Unsloth-PEFT%20%2F%20QLoRA-blue?style=for-the-badge)
![Ollama](https://img.shields.io/badge/Ollama-Local%20Inference-black?style=for-the-badge&logo=ollama&logoColor=white)
![Langfuse](https://img.shields.io/badge/Langfuse-Observability-orange?style=for-the-badge)

### 🗄️ Vector Stores & Databases:
![Qdrant](https://img.shields.io/badge/Qdrant-Vector%20DB-DC2626?style=for-the-badge&logo=qdrant&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-Dense%20Search-00599C?style=for-the-badge)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

### 🛠️ Full-Stack & Backend:
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React%2018-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

### ☁️ Infrastructure & Developer Tools:
![Docker](https://img.shields.io/badge/Docker%20Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

---

## 🏆 Featured Projects

### 🩺 **[Clinical AI Assistant: Multi-Stage PEFT & Reasoning Alignment](https://github.com/metinyurdev)** *(Undergraduate Thesis)*
- **3-Stage Fine-Tuning Pipeline:** Aligned a `Qwen2.5-14B-Instruct` model across three consecutive phases (*Domain Knowledge ➔ Clinical Reasoning ➔ Ethical Guardrails*) using Unsloth (PEFT/QLoRA) while mitigating catastrophic forgetting.
- **Red-Teaming & Synthetic Data:** Built an automated data engine via Llama-3 generating adversarial counter-samples to enforce biomedical refusal protocols and safety guardrails.
- **Evaluation Framework:** Executed **LLM-as-a-Judge** scoring (GPT-4o-mini) and deconstructed formatting bias using **DeBERTa-v3 BERTScore** (achieving 72.67% semantic fidelity, +5.29 points over base), with a **99.00%** Clinical Safety score and **~91.00%** Hallucination Prevention Rate.
- **Local LLMOps:** Quantized final weights into GGUF format for private, zero-latency clinical deployment via Ollama, hosting adapters on Gated HuggingFace repos.

### 🛡️ **[NEXUS - Enterprise Multi-Agent Compliance Auditor](https://github.com/metinyurdev/nexus-compliance-agent)**
- **Agentic RAG Orchestration:** Hierarchical multi-agent framework powered by **LlamaIndex Core** and **OpenAI GPT-4o** orchestrating specialized sub-agents (*Contract Auditor, Regulation Specialist, Web Researcher via DDGS*).
- **Two-Stage Retrieval Pipeline:** Integrated **BAAI/bge-m3** (1024-dim dense embeddings) with a **BAAI/bge-reranker-base cross-encoder** to eliminate context loss.
- **Multi-Tenant Security:** Configured session-isolated, metadata-filtered vector namespaces in **Qdrant Vector DB** to prevent cross-session context leakage.
- **Full-Stack Observability:** Embedded a self-hosted **Langfuse** tracing stack over PostgreSQL to monitor token usage, latency, and tool execution spans in real time, containerized with **Docker Compose** alongside a **FastAPI + React (Vite/Tailwind)** UI.

### ⚡ **[NEXUS RAG - Enterprise Hybrid Search Engine](https://github.com/metinyurdev/nexus-rag)**
- **Hybrid Retrieval:** Combined dense semantic vector search (**FAISS**) with sparse keyword search (**BM25**) to maximize recall and precision.
- **Multi-Stage Processing:** Structured query transformation, cross-encoder reranking, and context compression to minimize prompt bloat and eliminate hallucinations.
- **Production-Ready Features:** Real-time token streaming via **Server-Sent Events (SSE)**, session-scoped document isolation, page-level citations, and automated evaluation using **RAGAS** (Faithfulness & Relevancy).
- **Tech Stack:** Python 3.10, FastAPI, React 18, Vite, Tailwind CSS, LangChain, Ollama, Docker Compose.

### 💾 **[Enterprise Text-to-SQL Full-Stack Platform](https://github.com/metinyurdev/text2sql_fullstack_app)**
- **Natural Language Database Querying:** AI-driven system translating complex natural language requests into optimized, executable PostgreSQL queries using open-source LLMs (Llama 3.2 via Ollama).
- **Security & Full-Stack Architecture:** High-concurrency **FastAPI** backend secured with granular **JWT-based authentication**, coupled with an interactive **React + Vite** frontend.

---

## 📝 Recent Articles & Publications

- 📖 **[RAG Systems Are Breaking the Barriers of Language Models: Here's How](https://hackernoon.com/u/metinyurdev)** *(HackerNoon)*
- 📖 **[How Retrieval and Generation Work Hand in Hand in RAG](https://hackernoon.com/u/metinyurdev)** *(HackerNoon)*
- 📖 **[The LLM Operating System: Transformers, Limitations, and the Need for Adaptation](https://hackernoon.com/u/metinyurdev)** *(HackerNoon)*

---

## 📫 Connect with Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/metin-yurduseven)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/metinyurdev)
[![Hugging Face](https://img.shields.io/badge/HuggingFace-FFCC00?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.com/metinyurdev)
[![HackerNoon](https://img.shields.io/badge/HackerNoon-00EB88?style=for-the-badge&logo=hackernoon&logoColor=black)](https://hackernoon.com/u/metinyurdev)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:metin.yrdsvn@gmail.com)

*Open to engineering collaborations, research initiatives, and advanced AI system architectures.*
