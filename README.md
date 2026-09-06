# Darshan Gowda M — Personal Portfolio & AI Engineering Showcase

[![Live Site](https://img.shields.io/badge/Live%20Portfolio-Darshan1704.github.io-1A56DB?style=flat-square&logo=googlechrome&logoColor=white)](https://darshan1704.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-darshangowdam1704-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/darshangowdam1704)
[![GitHub](https://img.shields.io/badge/GitHub-Darshan1704-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Darshan1704)
[![Email](https://img.shields.io/badge/Email-darshangowdam17%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:darshangowdam17@gmail.com)

Welcome to the official repository for my personal portfolio website, hosted on GitHub Pages at **[Darshan1704.github.io](https://darshan1704.github.io)**.

---

## 👨‍💻 About Me

I am an **AI Engineer** at **Tata Consultancy Services (TCS)** with ~2 years of industry and project experience specializing in **Production Generative AI Systems, RAG Pipelines, Multi-Agent Orchestration Workflows, and Cloud ML** (Azure & AWS).

- 🏢 **Current Role:** Assistant System Engineer — AI & Data at Tata Consultancy Services (Hyderabad, India)
- 🚀 **Systems Shipped:** 3 Production AI systems across Aviation, Healthcare, and Enterprise Reporting domains
- 🎯 **Target Roles:** AI Engineer · AI/ML Engineer · Forward Deployed Engineer · GenAI Engineer · LLM Engineer

---

## 🛠️ Technical Stack & Expertise

| Domain | Technologies & Frameworks |
| :--- | :--- |
| **GenAI & LLMs** | Azure OpenAI GPT-4o, Cohere command-r+, Anthropic Claude API, LangGraph, LangChain |
| **RAG & Search** | Qdrant, FAISS, BM25 / BM25Plus, Hybrid Dense-Sparse Search, TF-IDF, Cosine Similarity |
| **Prompt Engineering** | Few-Shot, JSON-Mode, Temperature Tuning, Hallucination Reduction, Verbatim Extraction |
| **Cloud Platforms** | AWS SageMaker, AWS S3, boto3, Azure OpenAI, Azure AI Studio |
| **Languages & APIs** | Python, SQL, Java, FastAPI, Streamlit, Node.js, HTML5/CSS3/JS |
| **ML & Data** | Scikit-learn, Random Forest, Feature Engineering, Pandas, Power BI |

---

## 🚀 Key Featured Projects

### 1. 🏥 Medical Device Regulatory Submission Assistant (Healthcare Domain)
* **Impact:** ~80% reduction in manual document search effort
* **Stack:** RAG · Qdrant · Cohere command-r-plus · FastAPI · PyMuPDF · TF-IDF · RapidFuzz
* **Summary:** End-to-end RAG pipeline for FDA 510(k) predicate discovery across a corpus of cleared medical device PDFs. Utilized dual-layer similarity (dense vector cosine search for Intended Use + TF-IDF sentence-level matching for technical characteristics) with automated compliant 510(k) summary generation.

### 2. ✈️ Vectorless PageIndex RAG (Aviation Domain)
* **Impact:** 6 retrieval improvements over baseline
* **Stack:** Azure OpenAI GPT-4o · BM25Plus · langextract · PyMuPDF
* **Summary:** Retrieval-augmented pipeline without embedding vectors — LLM-generated hierarchical document trees with entity enrichment (aircraft models, ATA codes, action keywords) and BM25Plus re-ranking for EASA Airworthiness Directive (AD) documents.

### 3. 📊 Agentic Report Generation System (Enterprise Reporting Domain)
* **Impact:** 2–3× faster throughput vs. sequential processing
* **Stack:** LangGraph · FAISS · BM25 · Azure OpenAI GPT-4o · FastAPI · Streamlit · asyncio
* **Summary:** 5-agent LangGraph pipeline (*Planner → Retrieval → Writer → Validation → Assembly*) with conditional routing and self-correcting validation loops. Integrated concurrent async processing and 70% FAISS dense + 30% BM25 sparse hybrid retrieval.

---

## 🏆 Achievements & Hackathons

- 🏅 **Rank #7** — *PromptWars: Hyderabad* — Google / hack2skill AI Hackathon (July 2026)
- 🏅 **Top 10** — *TCS Internal Hackathon* — AI/LLM & RAG track, selected from hundreds of internal submissions nationwide
- 🥉 **Rank #3** — *Inter-Departmental Mini Project Exhibition* — outperformed 25 competing teams
- 🏅 **Rank #5** — *DevHacks 1.0 National Level Hackathon* — competed against 150+ participants across India

---

## 📜 Certifications & Credentials

- 🟧 **Amazon Web Services (AWS):**
  - AWS Partner: Agentic AI Essentials (*March 2026*)
  - AWS Partner: Generative AI Essentials (*March 2026*)
- 🟦 **Microsoft:**
  - Microsoft Certified: Azure Fundamentals (AZ-900)
  - Microsoft Certified: Power Platform Fundamentals (PL-900)
- 🟨 **Anthropic Academy:**
  - Building with Claude API (*Verified*)
  - Intro to MCP & MCP Advanced Topics (*In Progress*)

---

## 📁 Repository Structure

```text
Darshan1704.github.io/
├── index.html                     # Main single-page portfolio layout & interactive modal viewer
├── README.md                      # Repository overview & documentation
└── assets/
    ├── Darshan_Gowda_M_Resume.pdf # Official Resume
    ├── Darshan_GowdaM_CV.pdf      # Detailed Curriculum Vitae
    └── certs/                     # Verified PDF credentials and certificates
```

---

## 🌐 Local Development & Deployment

This is a clean, dependency-free static website crafted with modern semantic HTML5 and vanilla CSS/JavaScript.

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Darshan1704/Darshan1704.github.io.git
   cd Darshan1704.github.io
   ```
2. **Preview locally:**
   - Open `index.html` directly in any web browser, or
   - Use Python's built-in HTTP server:
     ```bash
     python -m http.server 8000
     ```
   - Open `http://localhost:8000` in your browser.

3. **Deployment:**
   - Hosted automatically via **GitHub Pages** from the `main` branch root directory.

---

## 📬 Contact & Connect

- 📧 **Email:** [darshangowdam17@gmail.com](mailto:darshangowdam17@gmail.com)
- 💼 **LinkedIn:** [linkedin.com/in/darshangowdam1704](https://linkedin.com/in/darshangowdam1704)
- 📱 **Phone:** +91 77605 72027
- 💻 **GitHub:** [@Darshan1704](https://github.com/Darshan1704)

---
*© 2026 Darshan Gowda M. All rights reserved.*
