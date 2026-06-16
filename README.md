# 🥗 Nutrition Agent using IBM watsonx.ai

## Overview

Nutrition Agent is an AI-powered assistant built using IBM watsonx.ai Agent Lab. The project leverages IBM Granite foundation models, LangGraph, and LangChain to provide intelligent nutrition-related assistance and recommendations.

The agent is designed to answer nutrition queries, provide dietary guidance, analyze food-related information, and interact with users through a conversational interface powered by IBM Watsonx AI.

---

## Problem Statement

People often struggle to make informed nutritional decisions due to the abundance of conflicting information available online. This project aims to provide a reliable AI-powered nutrition assistant that can answer dietary questions and support healthier food choices.

---

## Solution

The Nutrition Agent uses IBM watsonx.ai foundation models to understand user questions and generate contextual responses. The agent architecture integrates:

- IBM Granite Foundation Models
- IBM watsonx.ai
- LangGraph Agent Framework
- LangChain Integration
- IBM Cloud Authentication

The agent processes user input, reasons through available tools, and generates nutrition-focused responses.

---

## Features

### 🍎 Nutrition Guidance
- Provides nutrition-related recommendations
- Answers dietary and food-related questions
- Supports healthy eating decisions

### 🤖 AI-Powered Conversations
- Natural language interactions
- Context-aware responses
- Conversational user experience

### ☁️ IBM Watsonx Integration
- Uses IBM Granite models
- Secure IBM Cloud authentication
- Enterprise-grade AI infrastructure

### 🔗 Agent-Based Architecture
- Built with LangGraph
- Supports tool-based reasoning
- Extensible design for future enhancements

---

## Technology Stack

| Category | Technology |
|-----------|------------|
| AI Model | IBM Granite 3.3 8B Instruct |
| AI Platform | IBM watsonx.ai |
| Agent Framework | LangGraph |
| LLM Framework | LangChain |
| Programming Language | Python 3.11 |
| Authentication | IBM Cloud API Key |
| SDK | ibm-watsonx-ai |

---

## Architecture

```text
User
  │
  ▼
Nutrition Agent
  │
  ▼
LangGraph Agent
  │
  ▼
IBM Granite Model
  │
  ▼
IBM watsonx.ai
  │
  ▼
Nutrition Response
```

---

## Project Workflow

1. User submits a nutrition-related query.
2. Agent receives and processes the request.
3. LangGraph manages reasoning and tool execution.
4. IBM Granite model generates the response.
5. Agent returns a structured answer to the user.

---

## Prerequisites

Before running the notebook, ensure you have:

- IBM Cloud Account
- IBM watsonx.ai Project
- IBM Cloud API Key
- Python 3.11+

---

## Installation

### Clone Repository

```bash
git clone https://github.com/amjathhussain31/IBM-Project.git
cd IBM-Project
```

### Install Dependencies

```bash
pip install langchain-ibm
pip install ibm-watsonx-ai
pip install langgraph
pip install requests
```

---

## Configuration

Provide your IBM Cloud API Key when prompted in the notebook:

```python
credentials = {
    "url": "https://us-south.ml.cloud.ibm.com",
    "apikey": "<YOUR_API_KEY>"
}
```

---

## Running the Project

Open the notebook:

```bash
jupyter notebook
```

Run:

```text
Nutrition Agent Standard Notebook.ipynb
```

Enter your nutrition-related question when prompted:

```text
Question: What foods are rich in protein?
```

Example Response:

```text
Foods rich in protein include eggs, chicken breast,
fish, lentils, beans, tofu, and Greek yogurt.
```

---

## Key Components

### Authentication
- IBM Cloud API authentication
- Bearer token generation

### Model Configuration

```python
model_id = "ibm/granite-3-3-8b-instruct"
```

### Agent Creation
- LangGraph ReAct Agent
- Memory management
- Tool integration

### Response Generation
- User query processing
- AI inference
- Structured output generation

---

## Repository Contents

### Nutrition Agent Standard Notebook.ipynb
Contains:
- Watsonx authentication
- Agent configuration
- Model setup
- Agent invocation workflow

### IBM PROJECT PPT.pptx
Project presentation containing:
- Problem statement
- Solution overview
- Architecture
- Results and demonstration

---

## Future Enhancements

- Food image recognition
- Calorie estimation
- Personalized meal planning
- Diet tracking dashboard
- Health report generation
- Mobile application integration

---

## Learning Outcomes

This project demonstrates:

- IBM watsonx.ai Agent Lab
- Foundation Model Integration
- LangGraph Agent Development
- LangChain Workflows
- IBM Cloud Authentication
- AI-powered Nutrition Assistance

---

## Acknowledgements

- IBM watsonx.ai
- IBM Granite Models
- LangChain
- LangGraph
- IBM Cloud
