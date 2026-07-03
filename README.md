<div align="center">
 


<h1 align="center"><strong>⚕️ Multi-Agent-Medical-Assistant :<h6 align="center">AI-powered multi-agentic system for medical diagnosis and assistance</h6></strong></h1>


</div>

----


## 📌 Overview <a name="overview"></a>

The **Multi-Agent Medical Assistant** is an **AI-powered chatbot** designed to assist with **medical diagnosis, research, and patient interactions**.  

🚀 **Powered by Multi-Agent Intelligence**, this system integrates:  
- **🤖 Large Language Models (LLMs)**  
- **🖼️ Computer Vision Models** for medical imaging analysis  
- **📚 Retrieval-Augmented Generation (RAG)** leveraging vector databases  
- **🌐 Real-time Web Search** for up-to-date medical insights  
- **👨‍⚕️ Human-in-the-Loop Validation** to verify AI-based medical image diagnoses  

### **What You’ll Learn from This Project** 📖  
🔹 **👨‍💻 Multi-Agent Orchestration** with structured graph workflows  
🔹 **🔍 Advanced RAG Techniques** – hybrid retrieval, semantic chunking, and vector search  
🔹 **⚡ Confidence-Based Routing** & **Agent-to-Agent Handoff**  
🔹 **🔒 Scalable, Production-Ready AI with Modularized Code & Robust Exception Handling**  


<!-- The **Multi-Agent Medical Assistant** is an advanced AI-powered chatbot system designed to assist in medical diagnosis, research, and patient interactions.

Using a **Multi-Agentic framework**, this assistant integrates **Large Language Models, Computer Vision Models, Retrieval Augmented Generation leveraging Vector Database**, and **Web Search** to provide **accurate**, **reliable**, and **up-to-date** medical insights.

This project serves as a **comprehensive resource** for learning and implementing **GenAI with multi-agent orchestration**. It demonstrates **advanced Retrieval-Augmented Generation (RAG)**, integrating **vector search with hybrid retrieval techniques**, **efficient chunking strategies respecting document semantic boundaries**, **confidence-based routing**, **agent-to-agent handoff**, **real-time web search capabilities**, **human-in-the-loop validation** and more. The system incorporates **specialized AI agents** for medical reasoning, diagnosis, and research retrieval, all working seamlessly through a structured graph workflow. Developers will gain insights into **modular agentic AI solution design, and robust exception handling** — ensuring **scalability and production readiness**.

For learners: Refer `agents/README.md` for detailed explanation of the agentic workflow. -->

---

## 🛡️ Technical Flow Chart  <a name="technical-flowchart"></a>

![Technical Flow Chart](assets/final_medical_assistant_flowchart_light_rounded.png)

---

<!-- ## 🌟 Key Features  <a name="key-features"></a>
✅ **Multi-Agent System** – Separate agents handle different tasks (diagnosis, retrieval, reasoning, etc.).  
✅ **RAG-based Retrieval** – Uses Qdrant for vector search & hybrid retrieval techniques.  
✅ **Medical Image Analysis** – Supports **brain tumor segmentation, chest X-ray disease detection, and skin lesion classification**.  
✅ **Web Search Agent** – Fetches the latest medical research when required.  
✅ **Confidence Score Check** – Ensures high accuracy with log probability-based verification.  
✅ **Speech-to-Text & Text-to-Speech** – Uses **Eleven Labs API** for voice interactions.  
✅ **Human-in-the-Loop Verification** – Medical professionals validate the AI’s results before final output.  
✅ **Intuitive UI** – Built for seamless user experience.  

---

## 🛠️ Tech Stack  <a name="tech-stack"></a>
🔹 **Backend**: FastAPI 🚀  
🔹 **Multi-Agent Orchestration**: LangGraph + LangChain 🤖  
🔹 **Vector Database**: Qdrant (for retrieval-augmented generation) 🔍  
🔹 **Medical Image Analysis**: Computer vision models (Brain Tumor - Semantic Segmentation, Chest X-ray - Object Detection, Skin Lesion - Classification) 🏥  
🔹 **Speech Processing**: Eleven Labs API 🎙️  
🔹 **UI**: HTML, CSS, JS 🌐  
🔹 **Deployment**: Docker 🛠️   -->

## ✨ Key Features  <a name="key-features"></a>

- 🤖 **Multi-Agent Architecture** : Specialized agents working in harmony to handle diagnosis, information retrieval, reasoning, and more

- 🔍 **Advanced Agentic RAG Retrieval System** :

  - Docling based parsing to extract text, tables, and images from PDFs.
  - Embedding markdown formatted text, tables and LLM based image summaries.
  - LLM based semantic chunking with structural boundary awareness.
  - LLM based query expansion with related medical domain terms.
  - Qdrant hybrid search combining BM25 sparse keyword search along with dense embedding vector search.
  - HuggingFace Cross-Encoder based reranking of retrieved document chunks for accurate LLM reponses.
  - Input-output guardrails to ensure safe and relevant responses.
  - Links to source documents and images present in reference document chunks provided with reponse.
  - Confidence-based agent-to-agent handoff between RAG and Web Search to prevent hallucinations.

- 🏥 **Medical Imaging Analysis**  
  - Brain Tumor Detection (TBD)
  - Chest X-ray Disease Classification
  - Skin Lesion Segmentation

- 🌐 **Real-time Research Integration** : Web search agent that retrieves the latest medical research papers and findings

- 📊 **Confidence-Based Verification** : Log probability analysis ensures high accuracy in medical recommendations

- 🎙️ **Voice Interaction Capabilities** : Seamless speech-to-text and text-to-speech powered by Eleven Labs API

- 👩‍⚕️ **Expert Oversight System** : Human-in-the-loop verification by medical professionals before finalizing outputs

- ⚔️ **Input & Output Guardrails** : Ensures safe, unbiased, and reliable medical responses while filtering out harmful or misleading content

- 💻 **Intuitive User Interface** : Designed for healthcare professionals with minimal technical expertise

---

## 🛠️ Technology Stack  <a name="technology-stack"></a>

| Component | Technologies |
|-----------|-------------|
| 🔹 **Backend Framework** | FastAPI |
| 🔹 **Agent Orchestration** | LangGraph |
| 🔹 **Document Parsing** | Docling |
| 🔹 **Knowledge Storage** | Qdrant Vector Database |
| 🔹 **Medical Imaging** | Computer Vision Models |
| | • Brain Tumor: Object Detection (PyTorch) |
| | • Chest X-ray: Image Classification (PyTorch) |
| | • Skin Lesion: Semantic Segmentation (PyTorch) |
| 🔹 **Guardrails** | LangChain |
| 🔹 **Speech Processing** | Eleven Labs API |
| 🔹 **Frontend** | HTML, CSS, JavaScript |
| 🔹 **Deployment** | Docker, GitHub Actions CI/CD |

---

