# 🤖 AI-Powered Multi-Agent Research Assistant

An autonomous research system that uses multiple AI agents to perform web research, analyze information, generate reports, and evaluate output quality. The project demonstrates Agentic AI, tool calling, ReAct reasoning, and multi-agent collaboration using LangChain and OpenAI.

---

## 🚀 Features

* Multi-agent architecture
* Autonomous web research
* Real-time information gathering
* Web scraping and content extraction
* AI-generated research reports
* Report quality evaluation using a Critic Agent
* ReAct-based reasoning and tool usage
* Interactive Streamlit interface

---

## 🏗️ System Architecture
![Project Flow](https://github.com/ayushbagahe/AI-Powered-Multi-Agent-Research-Assistant/blob/main/flow.jpg)
### 🔍 Research Agent

* Searches the web for relevant information
* Collects and analyzes sources
* Extracts key insights

### ✍️ Report Writer Agent

* Synthesizes gathered information
* Generates structured research reports
* Organizes findings into clear sections

### 🧠 Critic Agent

* Reviews generated reports
* Identifies weaknesses and gaps
* Provides improvement suggestions

---

## 🛠️ Tech Stack

### AI & LLMs

* OpenAI GPT Models
* LangChain
* ReAct Framework

### Search & Data Collection

* Tavily Search API
* BeautifulSoup4
* Requests

### Frontend

* Streamlit

### Backend

* Python

### Environment Management

* python-dotenv

---

## 💡 Skills Demonstrated

### Artificial Intelligence

* Agentic AI Systems
* Multi-Agent Workflows
* Prompt Engineering
* Tool Calling
* Autonomous Reasoning

### LLM Engineering

* LangChain Development
* ReAct Agents
* Workflow Orchestration
* AI Application Development

### Software Engineering

* Python Programming
* API Integration
* Modular Architecture
* Error Handling
* Environment Management

### Data Engineering

* Web Scraping
* Information Extraction
* Search Integration
* Data Processing

---

## ⚙️ Workflow

1. User submits a research query.
2. Research Agent gathers information from the web.
3. Scraping tools extract relevant content.
4. Report Writer Agent generates a research report.
5. Critic Agent evaluates and improves report quality.
6. Final report is displayed in the Streamlit application.

---

## 📂 Project Structure

```bash
├── app.py
├── agents.py
├── tools.py
├── prompts.py
├── requirements.txt
├── .env
└── README.md
```

## 🚀 Installation

### Clone the repository

```bash
git clone https://github.com/your-username/Multi-Agent-Research-Assistant.git
cd Multi-Agent-Research-Assistant
```

### Create a virtual environment

```bash
python -m venv .venv
```

### Activate the virtual environment

Windows:

```bash
.venv\Scripts\activate
```

Mac/Linux:

```bash
source .venv/bin/activate
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Configure environment variables

Create a `.env` file:

```env
OPENAI_API_KEY=your_openai_api_key
TAVILY_API_KEY=your_tavily_api_key
```

### Run the application

```bash
streamlit run app.py
```

---

## 🎯 Resume Highlights

* Built an AI-powered multi-agent research system for web research, report generation, and quality evaluation.
* Integrated Tavily Search and BeautifulSoup for real-time data collection and information extraction.
* Implemented ReAct-based agent workflows with tool calling and autonomous reasoning.
* Developed an interactive Streamlit interface for research query submission and report visualization.
* Improved output quality through an automated Critic Agent.

---

## 🔮 Future Improvements

* LangGraph integration
* RAG-based retrieval system
* Memory-enabled agents
* PDF report export
* Source citation tracking
* Vector database integration
* Multi-modal document support

---

## 📜 License

This project is licensed under the MIT License.
