# 🦜 Build Smarter AI Apps — Empower LLMs with LangChain

![Language](https://img.shields.io/badge/Language-Python%203.11-3776AB?style=flat-square&logo=python&logoColor=white)
![Framework](https://img.shields.io/badge/Framework-LangChain%200.2-FF6B35?style=flat-square)
![LLM](https://img.shields.io/badge/LLM-Llama%203.3%2070B%20%7C%20Granite%203.3-052FAD?style=flat-square&logo=ibm&logoColor=white)
![Platform](https://img.shields.io/badge/Platform-IBM%20Watsonx.ai-052FAD?style=flat-square&logo=ibm&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=flat-square)

---

## 📌 Project Overview

Comprehensive hands-on lab covering **all core LangChain concepts** — 
from basic LLM calls to agents, RAG pipelines, memory, and chains. 
Uses **Meta Llama 3.3 70B** and **IBM Granite 3.3 8B** via IBM 
Watsonx.ai across 7 exercises covering real-world AI app patterns.

**Domain:** LangChain — Full Framework Mastery  
**LLMs:** meta-llama/llama-3-3-70b-instruct + ibm/granite-3-3-8b-instruct  
**Platform:** IBM Watsonx.ai  

---

## 🛠️ Tech Stack

| Component | Technology |
|---|---|
| LLM Framework | LangChain 0.2 + langchain-ibm |
| LLMs | Llama 3.3 70B + Granite 3.3 8B (Watsonx) |
| Vector Store | ChromaDB / FAISS |
| Document Loaders | PDF loader + URL/website loader |
| Output Parsers | JSON parser + CSV list parser |
| Memory | ConversationBufferMemory |
| Chains | LLMChain + LCEL |

---

## 📚 9 Core LangChain Concepts Covered

### 1. 🤖 Model & Chat Model
```python
model_id = 'meta-llama/llama-3-3-70b-instruct'
llama_llm = WatsonLLM(model=model)
llama_llm.invoke([SystemMessage(...), HumanMessage(...)])
```

### 2. 📝 Prompt Templates
- `PromptTemplate.from_template()` — string templates with variables
- `ChatPromptTemplate` — multi-role chat prompts
- `MessagesPlaceholder` — dynamic message injection

### 3. 📤 Output Parsers
- **JSON parser** — structured dict output
- **Comma-separated list parser** — list output

### 4. 📄 Documents & Loaders
- `Document` object — page_content + metadata
- **PDF loader** — extract text from PDFs
- **URL/website loader** — scrape web content
- `RecursiveCharacterTextSplitter` — chunk documents

### 5. 🔍 Embeddings, Vector Stores & Retrievers
- Embedding models for semantic search
- Vector store-backed retrievers
- Parent document retrievers
- `RetrievalQA` chain

### 6. 🧠 Memory
- `ChatMessageHistory` — conversation log
- `ConversationBufferMemory` — context-aware chatbot

### 7. ⛓️ Chains
- Simple chain: `LLMChain` (traditional)
- LCEL modern approach: `prompt | llm | parser`
- Sequential chains — multi-step processing

### 8. 🛠️ Tools & Agents
- Custom tool creation
- Toolkits
- Agent construction with tool-use

---

## 🎯 7 Hands-On Exercises

| # | Exercise | Skill |
|---|---|---|
| 1 | Compare Llama vs Granite with different temperatures | Model parameter tuning |
| 2 | JSON output parser for structured responses | Output parsing |
| 3 | Document loaders + text splitters | Document processing |
| 4 | Simple RAG retrieval system | Vector retrieval |
| 5 | Chatbot with memory | Conversational AI |
| 6 | Multi-step processing with chains | LCEL chaining |
| 7 | LangChain agent with basic tools | Tool-use agents |

---

## 🎓 Skills Demonstrated

- LangChain full framework — Models, Prompts, Parsers, Chains, Agents
- IBM Watsonx.ai integration — Llama 3.3 70B + Granite 3.3 8B
- PDF and URL document loading + chunking
- Vector store retrieval + RetrievalQA pipeline
- Conversation memory with ConversationBufferMemory
- LCEL (LangChain Expression Language) modern chaining
- JSON + CSV output parsing
- Tool creation and agent construction
- Multi-step sequential chain processing

---

## 📜 Certifications

| Certification | Issuer | Platform |
|---|---|---|
| IBM Data Science Professional Certificate | IBM | Coursera |
| IBM Generative AI Professional Certificate | IBM | Coursera |
| IBM Agentic AI with RAG Certificate | IBM | Coursera |
| IBM RAG and Agentic AI Professional Certificate | IBM | Coursera |

---

## 🤝 Connect with Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Leela%20A-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/leela-a)
[![Gmail](https://img.shields.io/badge/Gmail-attotaleelaissak@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:attotaleelaissak@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Leelaissakattaota-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Leelaissakattaota)
