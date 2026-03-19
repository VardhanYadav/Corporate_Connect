# 🏢 Corporate Connect

> A role-based corporate management platform powered by ML, Tableau analytics, and intelligent chatbot navigation — built to streamline HR decision-making and workforce insights.

---

## 📌 Overview

**Corporate Connect** is a full-stack enterprise management system that supports three distinct user roles — **Employee**, **HR**, and **Manager** — each with dedicated dashboards, analytics, and workflow tools. The platform integrates machine learning, sentiment analysis, and data visualization to enable data-driven decisions across all levels of an organization.

---

## 🗂️ Architecture

```
Corporate Connect
│
├── Public Pages
│   ├── About
│   ├── T&C
│   └── FAQ
│
└── Login
    ├── 👤 Employee
    │   ├── Graph Neural Network (Employee Insights)
    │   ├── KPIs Dashboard (Tableau)
    │   ├── Feedback & Sentiment Analysis
    │   │   └── [Exist / Exit / Fire]
    │   ├── Team Detail / Individual Detail
    │   └── Chatbot Navigation
    │
    ├── 🧑‍💼 HR
    │   ├── Company Trends & KPIs (Tableau)
    │   ├── ML Model for Hiring (Resume Dataset)
    │   ├── Fire / Exit Poll
    │   └── Chatbot Navigation
    │
    └── 📊 Manager
        ├── KPI Dashboard
        ├── Team Allocation
        ├── Salary Distribution
        ├── Company-Client Bond
        └── Chatbot Navigation
            
[All roles] ──► Report Module ──► End
```

---

## ✨ Features

### 👤 Employee Portal
- **Graph Neural Network** — Visual insights into employee connections and org-level relationships
- **KPI Dashboard (Tableau)** — Real-time personal performance metrics
- **Feedback & Sentiment Analysis** — NLP-powered sentiment scoring on employee feedback
- **Exist / Exit / Fire Poll** — Structured surveys with automated analysis
- **Team & Individual Detail View** — Drill-down into team composition and individual profiles
- **Chatbot Navigation** — Conversational interface for guided platform navigation

### 🧑‍💼 HR Portal
- **Company Trends & KPIs (Tableau)** — Macro-level company health visualizations
- **ML-Powered Hiring Model** — Resume-based candidate screening using a trained ML classifier
- **Fire / Exit Poll Analysis** — Automated aggregation and insight from departure surveys
- **Chatbot Navigation** — HR-specific guided workflows

### 📊 Manager Portal
- **KPI Dashboard** — High-level key performance indicators for managerial oversight
- **Team Allocation** — Assign and visualize team structures and headcount
- **Salary Distribution** — Pay equity and distribution analytics
- **Company-Client Bond Management** — Track and manage client relationship metrics
- **Chatbot Navigation** — Smart navigation for manager-specific modules

### 📋 Unified Report Module
All roles converge into a **centralized Report Module** that consolidates outputs from individual workflows into downloadable, shareable reports.

---

## 🧠 Tech Stack

| Layer | Technology |
|---|---|
| Data Visualization | Tableau |
| ML / Hiring Model | Python (scikit-learn / TensorFlow) |
| Sentiment Analysis | NLP (VADER / BERT) |
| Graph Neural Network | PyTorch Geometric / DGL |
| Chatbot | NLP-based Navigation Bot |
| Frontend | React.js / HTML / CSS |
| Backend | Python (Flask / Django) / Node.js |
| Database | PostgreSQL / MongoDB |
| Auth & Roles | JWT / Role-Based Access Control (RBAC) |

---

## 🚀 Getting Started

### Prerequisites

- Python 3.9+
- Node.js 18+
- Tableau Desktop / Tableau Public (for visualization)
- PostgreSQL or MongoDB

---

## 📁 Project Structure

```
corporate-connect/
├── backend/
│   ├── models/            # ML models (hiring, sentiment)
│   ├── api/               # REST API endpoints
│   ├── analytics/         # GNN, KPI logic
│   └── chatbot/           # Chatbot engine
├── frontend/
│   ├── src/
│   │   ├── pages/         # Employee, HR, Manager views
│   │   ├── components/    # Shared UI components
│   │   └── services/      # API service calls
├── tableau/               # Tableau workbooks (.twbx)
├── datasets/              # Resume dataset, poll data
├── docs/                  # Architecture diagrams, API docs
└── README.md
```

---

## 📊 ML Models

### 🔍 Resume-Based Hiring Model
- Trained on a labeled resume dataset
- Features: skills extraction, experience scoring, keyword matching
- Output: hire / reject recommendation with confidence score

### 💬 Sentiment Analysis
- Applied to employee feedback forms and exit/fire polls
- Classifies sentiment as Positive / Neutral / Negative
- Aggregated insights surfaced on HR dashboard

### 🕸️ Graph Neural Network
- Models organizational relationships between employees
- Surfaces hidden collaboration patterns and network influence metrics

---

## 📄 License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

---

---

> _Corporate Connect — Empowering every role with data, intelligence, and seamless navigation._
