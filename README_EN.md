# 🧭 QA Systems Hub: Question-Answering Systems Navigation Repository

This repository is a "navigation project" that compiles and organizes multiple mainstream question-answering system implementations, including traditional QA technologies and cutting-edge Large Language Model (LLM)/Agent architectures. It's suitable for developers, researchers, and product managers interested in question-answering systems to quickly understand and navigate to relevant resources.

---

## 🧱 Project Positioning

📌 `QA Systems Hub` itself does not contain specific code implementations, but rather:

- Unified collection of various QA technology sub-projects
- Brief explanations and comparisons of each QA type
- Provides applicable scenarios, advantages/disadvantages, and engineering recommendations
- Explains how to combine them into **Hybrid QA** in enterprise scenarios

---

## 🌐 QA Systems Navigation Overview

| QA Type | Description | Project Link | Status |
|---------|-------------|--------------|--------|
| **FQA** | Frequently QA: High-frequency Q&A based on semantic matching and retrieval of historical Q&A pairs. | [FQA-System](https://github.com/EasonWong0327/Hybrid-FQA-System) | ✅ Completed |
| **KBQA** | Knowledge-Based QA: Based on knowledge graphs, structured triple semantic queries. | [To-Be-Add: KBQA-System]() | ⏳ In Development |
| **Multimodal QA** | Multimodal Q&A: Supports mixed inputs like images + text. | [To-Be-Add: Multimodal-QA-System]() | ⏳ In Development |
| **Text-to-SQL QA** | Natural language to SQL conversion for structured database Q&A. | [To-Be-Add: Text2sql-QA-System]() | ⏳ In Development |
| **LLM-based QA** | Document Q&A and knowledge retrieval-augmented Q&A (RAG) based on large language models. | [Hybrid-RAG-System](https://github.com/EasonWong0327/Hybrid-RAG-System) | ✅ Completed |
| **Agent-based QA** | Agent Q&A supporting tool calling, long-chain reasoning, and task decomposition (like ReAct, AutoGPT style). | [To-Be-Add: Agent-QA-System]() | ⏳ In Development |

---

## 🧠 Enterprise QA Systems are Typically Hybrid QA

In actual business scenarios, a single QA system cannot meet all requirements. Enterprises often adopt **Hybrid QA** strategies, integrating multiple Q&A capabilities as needed:

- Intent recognition → Decide to enter KBQA / LLM QA / Text-to-SQL paths
- Document Q&A (RAG) combined with structured knowledge queries
- Agent calling external tools + multi-round reasoning chains (CoT, ReAct)

📌 This repository does not directly implement Hybrid QA, but provides a collection of "capability components" for building it.

> 👉 We recommend you choose appropriate component combinations based on your specific scenarios.

---

## 📚 Recommended Reading Order (Role-based Suggestions)

| Role | Recommended Order |
|------|-------------------|
| **Students / Beginners** | FQA → KBQA → LLM QA |
| **Researchers** | KBQA / Text-to-SQL / Multimodal QA |
| **Engineering Practitioners** | LLM QA → Agent-based QA → Hybrid QA Combination |
| **Product Designers** | Module introductions + Hybrid QA scenario cases |


---

## 📜 License

MIT License, welcome to Fork, learn, and develop further.

---

For suggestions or collaboration, feel free to raise issues or start discussions!

**Author**: [ EasonWong ]  
**Email**: eason0912happy@gmail.com  

---

## 🌐 Language Navigation

- [中文版 README](README.md) - Chinese version
- [English README](README_EN.md) - English version 