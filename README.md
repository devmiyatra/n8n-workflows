# AI Automation Workflows using n8n

This repository contains a collection of **AI-powered automation workflows built using n8n**.

These workflows demonstrate how AI agents, APIs, and automation tools can be integrated together to build practical systems such as:

* AI content automation
* HR knowledge assistant
* lead generation systems
* messaging bots
* workflow-based AI agents

These projects were built as part of my **AI Internship at Mirai School of Technology**, where the focus was on practical implementation of AI tools and automation systems.

---

# Technologies Used

• n8n – workflow automation platform
• OpenAI – AI language models and AI agents
• Pinecone – vector database for semantic search
• Tavily Search – AI research tool
• Google Drive – document storage
• Google Sheets – structured data storage
• Telegram Bot API – messaging automation
• LinkedIn APIs – content automation
• HTTP APIs – external integrations

---

# Featured Projects

## 1. AI LinkedIn Automation

An AI-powered workflow that automates the process of **researching topics and generating LinkedIn posts**.

### How it works

1. The workflow receives a topic request.
2. Tavily Search is used to research the topic.
3. The results are sent to an AI model.
4. OpenAI generates a structured LinkedIn post.
5. The output is formatted and prepared for publishing.

### Tools Used

• n8n
• OpenAI
• Tavily Search
• LinkedIn APIs

### Key Learning

This project helped me understand how **AI models and automation tools can be combined to automate content creation workflows**.

---

## 2. AI HR Assistant Bot (RAG Based)

An AI-powered HR assistant designed to answer questions using internal company documents.

This system uses **Retrieval Augmented Generation (RAG)**.

### How it works

1. HR documents are loaded from Google Drive.
2. Documents are split into smaller sections.
3. Embeddings are generated for each section.
4. Embeddings are stored in Pinecone vector database.
5. When a user asks a question, the system retrieves the most relevant information.
6. The AI model generates a contextual answer.

### Tools Used

• n8n
• OpenAI
• Pinecone
• Google Drive
• Embeddings

### Key Learning

This project helped me understand how **vector databases and AI models can be used together to build knowledge-based assistants**.

---

# Complete Workflow List

This repository contains multiple automation workflows:

### AI & Automation

• AI LinkedIn Automation
• AI HR Assistant Bot (RAG)
• AgentWorks AI automation workflow

### Messaging & Bots

• Telegram AI Bot
• HR Chatbot Workflow

### Data Automation

• Google Maps Lead Scraper
• LinkedIn Job Finder Automation

### Form & Email Automation

• Contact Form Automation
• Email Integration Workflow
• Email Automation System

### Scheduling & Booking

• Physio Appointment Automation

### Human in the Loop AI

• Human-in-the-loop Workflow 1
• Human-in-the-loop Workflow 2

### Knowledge Systems

• Google Drive RAG Setup

### API Automation

• Space Exploration API Workflow

Each workflow demonstrates how **different APIs and AI tools can be connected using n8n automation workflows**.

---

# Project Structure

```text
n8n-workflows
│
├── workflows
│   ├── 1_email workflow.json
│   ├── 3_contact us form.json
│   ├── 5_AI agent.json
│   ├── 6_physio appointment.json
│   ├── 7_Using Telegram Bot.json
│   ├── Agentworks Ai.json
│   ├── Dentist-Google-Maps-Scraper.json
│   ├── Email Integration (HR).json
│   ├── Google_Drive Setup Rag Based.json
│   ├── HR_bot.json
│   ├── Human-in-loop-1.json
│   ├── Human-in-loop-2.json
│   ├── LinkedIn Automation.json
│   ├── Linkedin_Job_Finder.json
│   └── space exploration.json
│
└── README.md
```

---

# Purpose of this Repository

The goal of this repository is to showcase **practical implementations of AI-powered automation systems**.

These workflows demonstrate how AI models, APIs, and automation tools can be integrated together to build intelligent systems that solve real-world problems.

---

# About Me

**Dev Miyatra**

I am interested in building **AI automation systems, AI agents, and intelligent workflows**.

This repository contains some of the projects I built while exploring AI automation and workflow design.

---

# Future Improvements

• More AI automation workflows
• Advanced AI agents and integrations
• Additional real-world automation use cases
