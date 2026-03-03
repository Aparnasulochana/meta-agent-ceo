# Meta-Agent CEO System

An autonomous AI system that works like a company CEO.
You give it a business problem. It automatically assigns the problem
to the right specialist AI agents, collects their reports, and gives
you one final executive decision.

---

## How It Works

1. You type a business query
2. The CEO AI reads it and decides which agents to activate
3. Each specialist agent analyzes the query from their domain
4. The CEO collects all reports and synthesizes a final decision

---

## Agents

- Management Agent — strategy, KPIs, resource allocation
- Marketing Agent — campaigns, market analysis, growth
- HR Agent — hiring, team structure, culture
- Innovation Agent — R&D, tech stack, new ideas
- Experimentation Agent — A/B testing, pilot programs, validation
- Product Analysis Agent — competitors, pricing, market fit

---

## Features

- RAG Pipeline — retrieves relevant knowledge before agents run
- LLM-as-Judge — scores each agent response for quality
- CEO Orchestrator — synthesizes all reports into executive brief
- Governance Layer — tracks agents, scores, runtime, and oversight

---

## Tech Stack

- Language: Python 3
- LLM: Llama 3.3 70B via Groq API
- Environment: Google Colab
- Library: Groq Python SDK

---

## How to Run

1. Open the notebook in Google Colab
2. Install the library
   pip install groq
3. Get a free API key from console.groq.com
4. Paste your key in the code
   API_KEY = "your-api-key-here"
5. Run all cells
6. Enter your business query when prompted

---

## Sample Query

We want to launch a new AI-based product in the Indian market next quarter. What should we do?

---

## Project Structure

meta-agent-ceo/
├── README.md
└── meta_agent_ceo.ipynb
