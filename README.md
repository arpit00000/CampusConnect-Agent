# README.md

## 🎓 College Admission Agent – AI-Powered RAG-Based Assistant

### Project Type: Agentic AI | Problem Statement No. 4 (IBM SkillsBuild for Academia 2025)

---

### 📅 Objective

To develop an AI-powered assistant that streamlines the college admission process using Retrieval-Augmented Generation (RAG). The agent answers student queries about eligibility, course details, application deadlines, and fees using institutional and official data.

---

### 🚀 Key Features

* Uses IBM Watsonx and IBM Granite LLM to power natural language conversations.
* Retrieves and summarizes documents like admission brochures, policies, and fee structures.
* Reduces manual work for faculty by automating repetitive admission FAQs.
* Enhances applicant experience with instant, data-grounded responses.
* Built and deployed entirely on IBM Watsonx platform (no custom code).

---

### 💻 Tech Stack

* IBM Watsonx.ai (Agent Lab)
* IBM Granite LLM (llama-3-70b-instruct)
* Retrieval-Augmented Generation (RAG)
* Google Search Tool (integrated within Watsonx)
* Indexed PDFs: Admission Policies, Course Info, Fee Structure

---

### 🔧 Deployment Process

1. Created a new Agent using IBM Watsonx Agent Lab.
2. Configured model: `llama-3-70b-instruct`.
3. Uploaded institutional admission data as a vector index.
4. Added Google Search as an external tool.
5. Defined initial prompt, sample queries, and instructions.
6. Previewed and tested using Watsonx Agent Preview interface.

---

### 🧰 Sample Questions Users Can Ask

* "What are the eligibility criteria for B.Tech admission?"
* "How much is the annual fee for MBA?"
* "When is the last date to apply for 2025 intake?"
* "Can you help me choose a course based on my interests?"

---

### 📊 Architecture Overview

Since this project is fully configured on IBM Watsonx without backend code or external services, there is **no custom architecture diagram** or flowchart. All configuration was completed using IBM's low-code tools.

---

### 📂 Repository Contents

```
College-Admission-Agent/
├── README.md
├── screenshots/                  # Screenshots of the agent working in IBM Watsonx
└── assets/
    ├── admission_policy.pdf      # Sample data used for vector indexing
    └── credentials/              # Optional: Certificate screenshots (RAG, AI, Cloud)
```

---

### 🏗️ License

This repository is for academic purposes only under the IBM SkillsBuild for Academia 2025 initiative.

---

### 💼 Author

**Arpit Jaiswal**
B.Tech CSE, VIT Chennai
Email: [jaiswalarpit438@gmail.com](mailto:jaiswalarpit438@gmail.com)
