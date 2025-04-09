# Multi-Agents for Customer Support

# 🤖 Multi-AI Agent System for Customer Support Inquiries

## 🧠 Project Summary

This project demonstrates a **Multi-AI Agent System** designed to simulate a realistic, intelligent customer support workflow using autonomous agents with role-specific capabilities. The system models how AI can collaborate and self-improve in a production-like customer service environment.

### 👥 Agents in the System

- 💬 **Customer Support Representative Agent**  
  Responds to customer inquiries by generating personalized, context-aware replies. This agent is equipped with a specialized tool that allows it to **scrape the contents of a website** to gather additional information and enrich its responses. This enables the agent to provide more accurate and tailored solutions.

- 🕵️ **Quality Assurance (QA) Agent**  
  Reviews the responses produced by the Support Agent to evaluate accuracy, tone, and completeness. The QA Agent is designed with the capability to:
  - **Ask clarifying questions**
  - **Delegate tasks back to the Support Agent** for refinement
  - **Ensure that responses meet a high-quality standard** before approval

## 🔄 Workflow Design

- 🔁 **Sequential Execution**  
  Agents operate in a defined order: the Support Agent responds first, followed by the QA Agent's review and validation.

- 🧠 **Persistent Memory**  
  The Crew is configured with memory, enabling agents to **learn from past interactions**, **improve future performance**, and **retain context** throughout the session.

- 🔧 **Tool Assignment by Role**  
  Only the **Support Agent** has access to the external scraping tool, mimicking how permissions and tools might be distributed in a real customer service team.

## 🔧 Key Features

- 🎯 **Goal-Oriented Agent Collaboration**
- 🧩 **Role-Specific Tool Use**
- 🤝 **Autonomous Task Delegation Between Agents**
- 📚 **Knowledge Retrieval via Web Scraping**
- 🧠 **Memory-Enabled Learning & Context Retention**

