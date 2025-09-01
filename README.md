# 🤖 SQL Agent Project – Natural Language to SQL 🚀  

## 📌 Overview  
This project is an **AI-powered SQL Agent** that allows anyone to query a **PostgreSQL database in Supabase** using **plain English**.  
The AI (Google Gemini / OpenAI) interprets user questions, converts them into SQL queries, executes them, and returns results in a clean, human-readable format.  

💡 In short: *Ask in English → Get instant SQL insights.*  

---

## ⚙️ Tech Stack  
- 🌀 **n8n** – Workflow Automation  
- 🗄️ **PostgreSQL (Supabase)** – Database  
- 🧠 **Google Gemini / OpenAI** – LLM for SQL generation
- 
---

## ✨ Features  
- 🔍 **Natural Language → SQL** conversion  
- 📊 Query live **Postgres (Supabase)** database  
- 🤝 **Context-aware memory** (follow-up questions supported)  
- 🎨 **Formatted results** (easy to read for business users)  
- 🔒 **Environment variables** for secure API keys  

---

## 📐 Architecture  
<p align="center">
  
<img width="859" height="414" alt="image" src="https://github.com/user-attachments/assets/42ae9173-17ce-4a9d-9ac3-7c210fa49bd3" />


</p>  

1. User enters a question in plain English.  
2. AI Agent (Gemini/OpenAI) converts it into SQL.  
3. SQL runs on **Supabase (Postgres)**.  
4. Results are returned back to the user.  

---

## 📊 Example  

**Query:**  
> "Show me the top 5 customers by revenue"  

**Output:**  
