Multi-agent Customer Support Automation
A CrewAI project where two AI agents handle a customer support inquiry, running fully locally with Ollama (llama3.2).

Agents
Senior Support Representative: scrapes the CrewAI docs and drafts an answer
Support Quality Assurance Specialist: reviews the draft and produces the final reply
Concepts covered
Role playing, focus, tools, cooperation, guardrails and memory

Tech
CrewAI, crewai-tools (ScrapeWebsiteTool), Ollama (llama3.2 + nomic-embed-text)

Run
Install Ollama, then run ollama pull llama3.2 and ollama pull nomic-embed-text
python -m venv .venv and .\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
Copy .env.example to .env
python main.py
The output is saved to support_response.md.