# 🤖 AI-Powered SQL Agent
> Transform natural language questions into SQL queries instantly with AI-driven workflow automation

<p align="center">
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white" />
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white" />
  <img src="https://img.shields.io/badge/Gemini_AI-4285F4?style=for-the-badge&logo=google&logoColor=white" />
</p>

## 📋 Prerequisites

- **Dataset Knowledge** - Users should be familiar with their database structure, table names, and column names for optimal query results
- **Basic Data Understanding** - Awareness of data types and relationships between tables helps generate more accurate queries

## 🎯 What This Solves

**Before:** Business users wait hours or days for simple data requests
- Managers blocked by technical barriers
- Analysts overwhelmed with repetitive queries
- Decision-making slowed by data access bottlenecks

**After:** Instant SQL generation from natural language
- Ask questions in plain English
- Get accurate results in seconds
- No SQL knowledge required

## ✨ Features

- 🗣️ **Natural Language Processing** - Ask questions like "Show me sales from last month"
- 🛡️ **Smart Validation** - Prevents invalid queries and ensures data accuracy
- ⚡ **Real-time Execution** - Instant results with built-in error handling
- 🔐 **Secure Database Access** - Safe query execution with proper permissions
- 📊 **Multiple Output Formats** - JSON, CSV, or formatted tables

## 🏗️ Architecture

```mermaid
graph TD
    A[👤 User Input<br/>Natural Language] --> B[🧠 Gemini AI<br/>Query Generation]
    B --> C[🔍 SQL Validator<br/>Schema Validation]
    C --> D[🗄️ PostgreSQL<br/>Query Execution]
    D --> E[⚙️ n8n Workflow<br/>Result Processing]
    E --> F[📋 Formatted Response<br/>Back to User]
    
    style A fill:#4fc3f7,stroke:#01579b,stroke-width:2px,color:#000
    style B fill:#ba68c8,stroke:#4a148c,stroke-width:2px,color:#000
    style C fill:#ffb74d,stroke:#e65100,stroke-width:2px,color:#000
    style D fill:#81c784,stroke:#1b5e20,stroke-width:2px,color:#000
    style E fill:#f06292,stroke:#880e4f,stroke-width:2px,color:#000
    style F fill:#4fc3f7,stroke:#01579b,stroke-width:2px,color:#000
```

## 🔧 Technology Stack

| Component | Technology | Purpose |
|-----------|------------|---------|
| **AI Engine** | Google Gemini | Natural language to SQL translation |
| **Database** | PostgreSQL + Supabase | Data storage and query execution |
| **Workflow** | n8n | Automation and result processing |

## 🎥 Demo Videos

| Feature | Demo Link | Description |
|---------|-----------|-------------|
| **Basic Workflow** | [📺 Watch Demo](https://github.com/user-attachments/assets/d61b4068-5f1b-426b-84c2-c056f980ddb7) | End-to-end query processing |
| **Error Handling** | [📺 Watch Demo](https://github.com/user-attachments/assets/a6c50ae6-3920-4387-af50-9796135c900a) | Validation and error responses |
| **Complex Queries** | [📺 Watch Demo](https://github.com/user-attachments/assets/59ac2379-ebee-40a4-8227-ede21f0ce541) | Advanced SQL generation |

## 📊 Performance Metrics

- **Query Generation**: < 15 seconds average response time
- **Accuracy Rate**: 95%+ for common business queries
- **Complex Query Handling**: 30 seconds average response time
- **Validation & Error Handling**: Provides accurate data with helpful suggestions
- **Uptime**: 99.9% availability target

## 🔮 Future Scope

- **Multi-Database Support** - MySQL and MongoDB integration
- **Enhanced Analytics** - Real-time dashboard with query insights

---

<p align="center">
<em>Made with ❤️ for the data community</em>
</p>
