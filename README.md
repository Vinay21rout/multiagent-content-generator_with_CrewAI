# Multi-Agent System with CrewAI

A multi-agent AI system built with [CrewAI](https://github.com/crewAIInc/crewAI) that uses collaborative agents to research and write professional articles on AI trends.

## Agents

| Agent | Role | Goal |
|-------|------|------|
| AI Researcher | Research Agent | Find useful and accurate information |
| Content Writer | Writer Agent | Write engaging and clear articles |

## Workflow

1. **Research Task** — The AI Researcher agent researches the latest AI trends (AI Agents, Robotics, Generative AI, Business Automation)
2. **Writing Task** — The Content Writer agent takes the research and produces a well-structured professional article

## Tech Stack

- Python 3.11
- [CrewAI](https://pypi.org/project/crewai/)
- [LangChain Google GenAI](https://pypi.org/project/langchain-google-genai/) — `gemini-2.5-flash`
- [python-dotenv](https://pypi.org/project/python-dotenv/)

## Setup

1. Clone the repo
```bash
git clone https://github.com/Vinay21rout/Multi-Agent-System_with_CrewAI.git
cd Multi-Agent-System_with_CrewAI
```

2. Create a virtual environment with Python 3.11
```bash
uv venv .venv --python 3.11
```

3. Install dependencies
```bash
uv pip install crewai langchain-google-genai python-dotenv ipykernel
```

4. Create a `.env` file
```
GOOGLE_API_KEY=your_gemini_api_key_here
OPENAI_API_KEY=NA
```

5. Run the notebook `agent.ipynb`

## Get API Key

- Gemini API key (free): https://aistudio.google.com/app/apikey
