# Automated Resume Evaluation System

Built an AI-powered workflow that automatically evaluates candidate resumes against a job description using n8n and large language models.  
The system extracts resume content, validates it, analyzes relevance, and generates structured, explainable evaluation results.

---

## 🚀 Project Overview

This project demonstrates how workflow automation and AI can be combined to build a scalable resume screening system similar to modern Applicant Tracking Systems (ATS).

The system is designed to:
- Automatically process newly uploaded resumes
- Evaluate candidate relevance using an LLM
- Generate structured, explainable outputs
- Store results for easy review and analysis

---

## 🎥 Demo Video

👉 **Watch the full demo here:**  
[🎬 Automated Resume Evaluation System](https://www.loom.com/share/07a8067762ab4f0b8fa0336261e238e5)

---

## ⚙️ System Architecture

**High-level flow:**

1. Resume uploaded to Google Drive  
2. Workflow is triggered automatically  
3. Resume text is extracted and validated  
4. AI evaluates resume against job description  
5. Structured results are written to Google Sheets  

---

## 🧠 Key Features

- **Event-driven automation** using n8n  
- **Text-based validation** to handle different file formats reliably  
- **AI-based semantic evaluation** instead of keyword matching  
- **Deterministic scoring** using low-temperature LLM configuration  
- **Explainable outputs** with clear reasoning  
- **Modular and scalable workflow design**

---

## 🧩 Tech Stack

- **n8n** – Workflow orchestration  
- **Google Drive API** – Resume ingestion  
- **Google Sheets** – Output storage  
- **OpenAI (LLM)** – Resume evaluation  
- **JSON-based data exchange**

---

## 🧪 Validation & Edge Case Handling

- Skips empty or invalid resumes  
- Avoids dependency on MIME type inconsistencies  
- Ensures meaningful content before AI evaluation  
- Designed for reliable execution at scale  

---

## 📈 Future Enhancements

- Resume scoring weights and ranking  
- Duplicate candidate detection  
- Role-based job description support  
- Analytics dashboard for recruiter insights  

---

## 📌 Author

**Ashwin**  
Built as a demonstration of workflow automation, AI reasoning, and scalable system design.

---

## 📎 Notes

This project is intended for learning, demonstration, and portfolio purposes.

