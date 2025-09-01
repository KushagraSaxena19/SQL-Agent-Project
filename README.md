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

## 🎥 Demo Workflow  

Here’s how the **AI-powered SQL Agent** works in action:  

1. User asks in plain English → *“Show me total sales by region in July”*  
2. Gemini LLM converts it → SQL query  
3. Query runs on **Supabase (Postgres DB)**  
4. Results returned back in **n8n workflow**  

```mermaid
flowchart TD
    A[User Query in English] --> B[Gemini LLM]
    B --> C[Generated SQL]
    C --> D[Supabase PostgreSQL DB]
    D --> E[n8n Workflow]
    E --> F[Results Returned to User]
