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

## 📌 Project Overview
This project allows business users and analysts to ask **plain English questions** such as:  
> “Show me total sales by region for the last 3 months.”  

The SQL Agent will automatically translate this into a **valid SQL query**, execute it on the database, and return the results.  
It ensures that queries are validated before execution, avoiding random or misleading data.

---

## 🎥 Demo Workflow  

```mermaid
flowchart TD
    A[User Query in English] --> B[Gemini LLM]
    B --> C[Generated SQL]
    C --> D[Supabase PostgreSQL DB]
    D --> E[n8n Workflow]
    E --> F[Results Returned to User]

👉 [Watch Demo Video](./demo/demo_workflow.mp4)

---

## ⚠️ Error & Validation Handling
The SQL Agent **never generates random results**. It strictly validates queries:  

- ❌ **Wrong data** → Returns a clear error message.  
- ✅ **Correct data** → Executes safely and shows results.  

👉 [Watch Error Handling Demo](./demo/error_validation.mp4)

---

## 💼 Why It’s Important for Business
- ⏳ **Saves analyst time** by automating repetitive SQL queries.  
- 👩‍💻 **Reduces dependency** on technical staff for simple reports.  
- ⚡ **Improves decision-making speed** with instant query results.  
- 🛡️ **Prevents human errors** in manual SQL writing.  

---

## 🔮 Extended Ways / Future Scope
- ✅ Integrate with **BI dashboards** (Power BI / Tableau).  
- ✅ Add **role-based access control** for query execution.  
- ✅ Implement **query optimization checks** for efficiency.  
- ✅ Support **multiple databases** beyond PostgreSQL.  
- ✅ Deploy as a **Slack/Teams chatbot** for non-technical users.  

---
