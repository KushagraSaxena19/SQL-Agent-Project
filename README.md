# 🚀 AI-Powered SQL Agent with Workflow Automation  

<p align="center"> 
  <img src="https://img.shields.io/badge/-PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" /> 
  &nbsp;&nbsp;
  <img src="https://img.shields.io/badge/-n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white" /> 
  &nbsp;&nbsp;&nbsp;
  <img src="https://img.shields.io/badge/-Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white" /> 
  &nbsp;&nbsp;&nbsp;
  <img src="https://img.shields.io/badge/-Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white" />
</p>

---

## 📖 Project Overview  

This project is an **AI-powered SQL Agent** built to make querying databases as simple as asking a question in English.  
It uses **Large Language Models (Google Gemini / OpenAI)** to understand natural language, generate **PostgreSQL queries**,  
and execute them on a **Supabase-hosted database**, all orchestrated with **n8n workflow automation**.  

✨ With this, even non-technical users can query a database in plain English without writing SQL.  

---

## 🛠️ Tech Stack  

- **n8n** → Workflow automation engine  
- **PostgreSQL (Supabase)** → Database  
- **Google Gemini** → LLM for query generation  

---

## 💡 Why is this Important for Businesses?  

- ⏱️ **Saves Time** → No more waiting for data teams. Anyone can ask questions in plain English.  
- 📊 **Better Decisions** → Business teams can access data instantly to make real-time decisions.  
- 👨‍💻 **Bridges Gap** → Removes the barrier between technical & non-technical teams.  
- 🛠️ **Automation Ready** → Integrates with n8n workflows to push insights directly to Slack, Gmail, or dashboards.  

👉 In short, it makes **data-driven decision making faster, easier, and accessible to everyone**.  

---

## 🛡️ Error Validation  

To ensure reliable query execution, the system includes **validation checks**:  
- ✅ **Schema Awareness** → If user asks for unavailable columns/tables, it responds with:  
  `"There is no available data to answer this query."`  
- ✅ **Clarification Questions** → If the query is ambiguous, the agent asks follow-ups before running SQL.  
- ✅ **Query Testing** → Every SQL is validated in a sandbox before execution.  

---

## 🎬 Demo  

### ✅ Example Query  

**User asks in plain English:**  
