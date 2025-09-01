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

## ❌ The Problem
In most companies, business users need analysts or developers to fetch even the simplest data.  
This creates a bottleneck:
- Managers waste time waiting for routine reports  
- Analysts spend hours writing repetitive SQL queries  
- Non-technical users feel blocked by technical barriers  

---

## ✅ The Solution
This project removes that bottleneck.  
An **AI-powered SQL Agent** allows users to ask questions in **plain English**.  
The agent automatically:
1. Translates the question into a SQL query  
2. Validates the query against available tables  
3. Executes safely  
4. Returns accurate results instantly  

⚡ Result → Business users get answers faster, analysts focus on real insights, and teams move quicker.  


---

## 🎥 Demo Workflow  

```mermaid
flowchart TD
    A[User Query in English] --> B[Gemini LLM]
    B --> C[Generated SQL]
    C --> D[Supabase PostgreSQL DB]
    D --> E[n8n Workflow]
    E --> F[Results Returned to User]
```
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

🚀 This project demonstrates how AI can simplify SQL workflows and empower businesses.  
📩 For collaboration or inquiries, reach out anytime!

