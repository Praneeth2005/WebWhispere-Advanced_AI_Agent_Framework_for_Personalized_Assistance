# PraneethsAIAgents

A Python-based AI agent system built using AgentOps.ai for transforming raw data into actionable insights through advanced analytics and machine learning.

## Features

- Web crawling and scraping capabilities
- Data transformation and analysis
- Agent-based architecture
- Built on AgentStack framework

## Requirements

- Python 3.11.0
- OpenAI 1.59.3
- CrewAI 0.83.0
- LangChain 0.3.14
- AgentStack 0.2.3
- LiteLLM 1.53.3

## Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/praneeths_ai_agents.git

# Install dependencies
pip install -r requirements.txt
```

## Project Structure

```
praneeths_ai_agents/
├── src/
│   ├── crew.py
│   ├── tools/
│   │   ├── file_read_tool.py
│   │   └── firecrawl_tool.py
├── config/
│   ├── agents.yaml
│   └── tasks.yaml
└── .env
```

## Usage

The system consists of multiple agents working together to process and analyze data:

- **Agent1_Scrapper**: Handles web scraping tasks
- **Agent2_Summarizer**: Processes and summarizes collected data

To run the project:

```python
from src.crew import PraneethsaiagentsCrew

crew = PraneethsaiagentsCrew()
crew.run()
```

## Configuration

Configure agents and tasks through YAML files in the config directory:
- `agents.yaml`: Define agent properties and capabilities
- `tasks.yaml`: Specify task workflows and parameters

## License

This project is licensed under the terms included in LICENSE.md