# Mental-Health-Companion-Agent
Autonomous AI system for mental health support using multi-agent architecture, sentiment analysis, and conversational AI.
# 🧠 Mental Health Companion Agent (MHA)

## 🚀 Overview
The **Mental Health Companion Agent (MHA)** is an AI-powered system designed to detect emotional distress, offer conversational support, and suggest helpful mental health resources. By combining **Autonomous AI Agents**, **NLP models**, and a simple **Gradio UI**, MHA acts as a first-line AI companion for users struggling with their emotions.

---

## 🎯 Motivation
With increasing mental health challenges globally, many people hesitate to seek professional help due to stigma, lack of awareness, or access issues. This project aims to **bridge the gap** by providing an AI-powered companion that offers **initial emotional support** and **guides users toward professional help if needed**.

---

## 🏗️ Tech Stack
| Component         | Technology Used |
|------------------|------------------|
| **Agent Framework** | CrewAI |
| **Sentiment Analysis** | RoBERTa (local) |
| **Conversation Generation** | Mistral 7B (local) |
| **UI Interface** | Gradio |
| **Orchestration** | Python |

---

## 📁 Folder Structure
```text
.
├── agents
│   ├── sentiment_agent.py
│   ├── conversation_agent.py
│   ├── resource_agent.py
│   └── __init__.py
├── workflows
│   ├── message_analysis_workflow.py
│   └── __init__.py
├── ui
│   └── gradio_app.py
├── run.py
├── requirements.txt
├── README.md
