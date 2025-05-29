# 🧭 QA Systems Hub: 问答系统导航仓库

本仓库是一个「导航型项目」，汇总并整理了多个主流问答系统的独立实现方式，包括传统 QA 技术与前沿大语言模型（LLM）/智能体（Agent）架构。适合对问答系统感兴趣的开发者、研究者、产品经理快速理解和跳转使用。

---

## 🧱 项目定位

📌 `QA Systems Hub` 本身不包含具体代码实现，而是：

- 统一收录各类问答技术子项目
- 对每种 QA 类型进行简要说明与对比
- 提供适用场景、优缺点、工程建议
- 解释企业级场景下如何组合为 **Hybrid QA**

---

## 🌐 QA 系统导航一览

| QA 类型 | 简介                                           | 项目链接                                                             |
|--------|----------------------------------------------|------------------------------------------------------------------|
| **FQA** | Frequently QA：高频问答，基于历史问答对的语义匹配与检索。          | [FQA-System](https://github.com/EasonWong0327/Hybrid-FQA-System) |
| **KBQA** | Knowledge-Based QA：基于知识图谱，结构化三元组语义查询。        | [To-Be-Add: KBQA-System]()                                       |
| **Multimodal QA** | 多模态问答：支持图像 + 文本等混合输入。                        | [To-Be-Add: Multimodal-QA-System]()                              |
| **Text-to-SQL QA** | 自然语言转 SQL，用于结构化数据库问答。                        | [To-Be-Add: Text2sql-QA-System]()                                |
| **LLM-based QA** | 基于大语言模型的文档问答、知识检索增强问答（RAG）。                  | [To-Be-Add: LLM-QA-System]()                                     |
| **Agent-based QA** | 智能体问答，支持工具调用、长链路推理、任务分解（如 ReAct、AutoGPT 风格）。 | [To-Be-Add: Agent-QA-System]()                                   |

---

## 🧠 企业级 QA 系统通常是 Hybrid QA

在实际业务中，单一 QA 系统难以满足所有需求。企业常采用 **Hybrid QA** 策略，按需集成多种问答能力：

- 意图识别 → 决定进入 KBQA / LLM QA / Text-to-SQL 等路径
- 文档问答（RAG）结合结构化知识查询
- Agent 调用外部工具 + 多轮思维链推理（CoT, ReAct）

📌 本仓库不直接实现 Hybrid QA，而是提供其构建「能力组件」的集合。

> 👉 推荐你根据具体场景选择合适组件组合。

---

## 📚 推荐阅读顺序（角色建议）

| 角色 | 推荐顺序 |
|------|----------|
| **学生 / 初学者** | FQA → KBQA → LLM QA |
| **研究人员** | KBQA / Text-to-SQL / Multimodal QA |
| **工程实践者** | LLM QA → Agent-based QA → 组合 Hybrid QA |
| **产品设计师** | 各模块简介 + Hybrid QA 场景案例 |

---

## 📌 TODO

- [ ] Text-to-SQL QA
- [ ] LLM-based QA
- [ ] Agent-based QA
- [ ] Multimodal QA
- [ ] KBQA

---

## 📜 License

MIT License，欢迎 Fork、学习、二次开发。

---

> 💬 如有建议或想合作，欢迎提 issue 或发起讨论！

