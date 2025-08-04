# 🌾 Smart Farming Assistance Agent

A smart AI-powered agent offering **real-time, localized agricultural advice** to small-scale farmers using **Retrieval-Augmented Generation (RAG)**. Built with IBM Watsonx and LangGraph, the agent helps users with crop recommendations, pest control, mandi prices, and more — all in local languages.

---

## 📌 Project Overview

- 🤖 **Name:** Smart Farming Assistance Agent  
- 🧠 **Built Using:** RAG + LangGraph + IBM Watsonx Assistant  
- 🧺 **Target Users:** Small-scale farmers across rural India  
- 🌐 **Primary Language Support:** English + Telugu  
- 🧾 **Key Features:**
  - Vector database-powered question answering
  - Web search fallback for latest market info
  - Domain-restricted logic (only answers farming-related queries)
  - Jargon-free, farmer-friendly explanations

---

## 🛠️ Setup Preview

| Configuration | Screenshot |
|---------------|------------|
| **Agent Setup** | ![Agent Setup Screenshot](./images/agent_setup.png) |

**Agent Description:**  
> Smart AI agent offering real-time, local farming advice using RAG for small-scale farmers.

---

## 💬 Sample Conversations

| Question | Agent Response |
|---------|----------------|
| **Q1:** *How can I protect my paddy crop from pests right now?* | Use Trichogramma japonicum, Chlorantraniliprole (0.4 ml/litre), neem-based bio-pesticides, and maintain good soil and irrigation health. |
| **Q2:** *What is the mandi rate for onions today in Hyderabad?* | The current mandi rate is **₹12.4/kg**. |

📸 Screenshot of actual interaction:  
![Chat Interaction](./images/chat_sample.png)

---

## ✅ Core Capabilities

- ✅ Answers only **farming-specific queries**  
- ❌ **Rejects unrelated questions** (e.g., celebrities, politics)  
- 🌍 Fetches fallback answers using **web or external sources** if vector DB lacks data  
- 🗣️ Supports **local languages like Telugu**  
- 👩‍🌾 Provides **clear, actionable advice** tailored for farmers

---

## 🧪 Example Policy Behavior

| Scenario | Behavior |
|----------|----------|
| **Relevant DB data exists** | Response is taken strictly from the vector DB |
| **Relevant data missing** | Agent checks training + performs web search (with notice) |
| **Out-of-domain question** | Politely refuses and redirects user |

Example:
- **Q:** Tomato prices in Nizamabad  
  → *₹950/quintal* from DB  
- **Q:** Who is Shah Rukh Khan?  
  → “I'm designed to assist with farming-related advice and information only…”

---

## 🔐 Domain Restriction Policy

> The agent is strictly trained and instructed to avoid topics **outside agriculture or smart farming**.  
> This ensures **credibility**, **focus**, and **farmer trust**.

---

## 📂 Folder Structure

📁 project-root/
├── README.md
├── images/
│ ├── agent_setup.png
│ ├── chat_sample.png
├── vector_db/
│ └── farming_knowledge.txt
└── agent_config/
└── instructions.yaml


---

## 🚀 Future Enhancements

- 🛰️ Integrate satellite data for soil & weather analysis  
- 📱 Deploy WhatsApp/IVR-based access for non-smartphone users  
- 📊 Add analytics to measure crop trends & price forecasting  

---

## 🤝 Credits

Developed with 💡 by Chiranjeevi Sai Moka  
Using IBM Cloud, LangGraph, and open agriculture datasets

---

## 📸 Screenshots

### 1. Agent Setup  
![Setup](./images/agent_setup.png)

### 2. Chat Preview  
![Chat](./images/chat_sample.png)

---

