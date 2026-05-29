# Multi-Agent Research System using CrewAI

## Overview

This project is a Multi-Agent AI Research System built using CrewAI. It simulates a collaborative research team where specialized AI agents work together to research a topic, analyze findings, and generate a structured report.

The workflow consists of:

- **Researcher Agent** – Collects information from multiple sources using web search.
- **Analyst Agent** – Analyzes findings to identify patterns, gaps, and opportunities.
- **Writer Agent** – Generates a concise and actionable report.

The final report is automatically saved as a Markdown file.

---

## Features

- Multi-Agent Collaboration
- Automated Web Research
- Information Analysis
- Strategic Insight Generation
- Report Generation
- Sequential Workflow Execution
- Tavily Search Integration
- OpenAI-powered Agents

---

## Architecture

```text
User Topic
     │
     ▼
Researcher Agent
(Web Search)
     │
     ▼
Research Findings
     │
     ▼
Analyst Agent
(Insight Extraction)
     │
     ▼
Strategic Analysis
     │
     ▼
Writer Agent
(Report Generation)
     │
     ▼
report.md
```

---

## Tech Stack

- Python
- CrewAI
- OpenAI API
- Tavily Search API
- LangChain
- Markdown

---

## Project Structure

```text
.
├── main.py
├── report.md
├── requirements.txt
└── README.md
```

---

## How It Works

### 1. Research Phase

The Researcher Agent:

- Searches the web using Tavily
- Collects information from multiple sources
- Identifies key facts and trends
- Provides source references

### 2. Analysis Phase

The Analyst Agent:

- Reviews research findings
- Detects patterns and trends
- Identifies opportunities and gaps
- Extracts actionable insights

### 3. Report Generation

The Writer Agent:

- Creates an executive summary
- Organizes findings
- Generates recommendations
- Produces a final report

---

## Installation

### Clone Repository

```bash
git clone https://github.com/your-username/multi-agent-research-system.git

cd multi-agent-research-system
```

### Install Dependencies

```bash
pip install crewai crewai-tools tavily-python
```

---

## Environment Setup

Set the following environment variables:

```env
OPENAI_API_KEY=your_openai_api_key
TAVILY_API_KEY=your_tavily_api_key
```

Or in Python:

```python
import os

os.environ["OPENAI_API_KEY"] = "your_openai_api_key"
os.environ["TAVILY_API_KEY"] = "your_tavily_api_key"
```

---

## Usage

Run the application:

```bash
python main.py
```

Enter a topic when prompted:

```text
Enter topic to research:
RAG
```

---

## Example Workflow

### Input

```text
AI Agents in Software Development
```

### Output

```markdown
# Executive Summary

AI Agents are increasingly being adopted to automate software development workflows and improve productivity.

# Key Findings

- Growing adoption across enterprises
- Improved developer productivity
- Increased use of agent orchestration frameworks

# Analysis

- Strong market growth
- Emerging opportunities in autonomous development tools

# Recommendations

- Invest in Agentic AI platforms
- Explore workflow automation opportunities
```

The complete report is saved as:

```text
report.md
```

---

## Sample Use Cases

- Market Research
- Technology Trend Analysis
- Business Intelligence
- Competitive Analysis
- Academic Research
- Product Research
- Industry Reports

---

## Learning Outcomes

This project demonstrates:

- Agentic AI
- Multi-Agent Systems
- CrewAI Framework
- Tool Calling
- Workflow Orchestration
- Prompt Engineering
- AI Automation
- Retrieval-Augmented Generation (RAG)
- LLM Application Development

---

## Future Enhancements

- Add Memory Support
- Integrate Vector Databases
- Support Parallel Agent Execution
- Generate PDF Reports
- Add Streamlit Frontend
- Add Multi-Model Support
- Human-in-the-Loop Validation

---

## Author

**Meghana Kollavajjala**

Built to explore Multi-Agent AI Systems, CrewAI, and Agentic AI workflows.
