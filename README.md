# 🚀 Job Automation Workflow (n8n + AI)

This repository contains an automated job-hunting workflow built using **n8n**, designed to simplify job applications, content posting, and resume-based job matching. The workflow integrates AI, scraping, and API automations to reduce manual effort and speed up job search activities.

---

## 🔥 Features

### ✅ 1. Auto Generate & Post Content (LinkedIn / Facebook)
- Creates professional job-related or tech-related posts using AI.
- Supports image + caption generation.
- Automatically publishes posts to **LinkedIn** or **Facebook Pages**.
- Allows scheduled posting (daily/weekly).

---

### ✅ 2. Resume Parsing & Profile Extraction
Uses AI to extract:
- Skills  
- Experience  
- Projects  
- Job roles  
- Preferred domains  
- Education  

This helps generate:
- Automated job descriptions  
- Optimized keyword-matched resumes  
- Profile summaries  

---

### ✅ 3. Automated Job Search (Across Platforms)
The workflow automatically searches for relevant jobs based on:
- Skills from resume  
- Preferred job roles (Data Analyst, AI/ML, Automation Engineer, Business Analyst, etc.)  
- Location preferences  
- Keywords (SQL, Python, Power BI, ML, etc.)

Sources include:
- LinkedIn Job Search  
- Naukri (scraping + API)  
- Indeed  
- Google Jobs  
- Company career pages  

---

### ✅ 4. Job Matching & Filtering
Ranks and filters jobs based on:
- Skill alignment  
- Role match  
- Experience requirement  
- Location preference  

The output is a list of **highly relevant jobs** ready for application.

---

### ✅ 5. Optional: Auto-Apply / Auto-Fill (Experimental)
- Auto-fills forms using stored data (name, resume, cover letter).
- Saves application confirmation data.
- Can notify via WhatsApp, Email, or Telegram.

*(User must verify before final submission for safety.)*

---

## 🧩 Workflow Components

- **AI Nodes**  
  - OpenAI / GPT for resume extraction and job role matching  
  - AI post generation  
  - Intent classification  

- **HTTP Request Nodes**  
  - Job site scraping  
  - LinkedIn/Facebook API calls  
  - Automation for form submissions  

- **Cron Triggers**  
  - Daily job search  
  - Scheduled posting  

- **Data Processing Nodes**  
  - Set  
  - Split In Batches  
  - Merge  
  - Function  

---

## ⚙️ Tech Stack

- **n8n (Low-code Automation)**
- **OpenAI API** (NLP, summarization, post generation)
- **Python (optional helper scripts)**
- **LinkedIn API / Facebook Graph API**
- **Web Scraping (N8N HTTP + AI extraction)**

---

## 📂 Folder Structure

