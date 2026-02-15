# 🦜🔗 Generative AI & LangChain Practice

Welcome to my laboratory for **Generative AI, Agents, and LLM Engineering**. This repository documents my journey from basic tool calling to advanced model fine-tuning and autonomous agent orchestration.

---

## 🌟 Flagship Project: SAP KBA Fine-Tuning & Knowledge Graphs
**Location:** [`/Dataset Extraction and LLM Fine tuning`](./Dataset%20Extraction%20and%20LLM%20Fine%20tuning)

A complete end-to-end pipeline designed to solve real-world enterprise problems using SAP Knowledge Base Articles (KBAs). This project demonstrates how to turn unstructured technical documentation into intelligent, queryable systems.

### 🚀 Key Features
| Module | Description | Tech Stack |
| :--- | :--- | :--- |
| **1. Knowledge Graph RAG** | Extracts entities (Products, Errors) and builds a visual graph connecting problems to solutions using **LightRAG** principles. | `Spacy`, `NetworkX`, `LangChain`, `BeautifulSoup` |
| **2. Unsupervised Clustering** | Automatically groups thousands of documents into semantic topics (e.g., "Database Crashes" vs "Installation Errors") without labels. | `Scikit-Learn` (K-Means, NMF), `TF-IDF`, `t-SNE` |
| **3. QLoRA Fine-Tuning** | Fine-tuned **TinyLlama-1.1B** on a custom-extracted Q&A dataset to answer SAP technical queries on consumer hardware (RTX 3050). | `Transformers`, `PEFT` (LoRA), `BitsAndBytes` (4-bit), `TRL` |



---

## 📚 LangChain Notebooks & Tutorials

### 🤖 Agents & Tool Orchestration
* **[`agents_in_langchain.ipynb`](./agents_in_langchain.ipynb)**: Building autonomous agents that can reason and decide which actions to take.
* **[`tool_calling_in_langchain.ipynb`](./tool_calling_in_langchain.ipynb)**: Fundamentals of binding tools to LLMs for structured outputs.
* **[`tools_in_langchain.ipynb`](./tools_in_langchain.ipynb)**: Deep dive into custom tool creation, `@tool` decorators, and ToolKits.

### 🛠️ Practical Use Cases
* **[`tool_calling_convert_currency_in_langchain.ipynb`](./tool_calling_convert_currency_in_langchain.ipynb)**: A real-world example of an agent capable of fetching real-time currency rates and performing conversions autonomously.

---

## 🛠️ Tech Stack
* **Orchestration:** LangChain, LangGraph
* **LLMs:** TinyLlama-1.1B, Mistral (via Ollama), OpenAI
* **Training:** QLoRA, SFTTrainer, Hugging Face PEFT
* **Data Engineering:** BeautifulSoup4, Pandas, Scikit-Learn

---

### 👨‍💻 Author
**Ubaid Ur Rehman**
* [LinkedIn](https://www.linkedin.com/in/ubaid-ur-rehman-422212177/)
* [Email](mailto:ubaidfr404786@gmail.com)
