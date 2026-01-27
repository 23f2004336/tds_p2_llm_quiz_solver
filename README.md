TDS LLM Quiz Solver

Autonomous LLM Agent for TDS Quiz Solving — a Python-based intelligent agent designed to autonomously solve structured quizzes using large language models. Built as part of the TDS Project 2 (Roll No: 23f2004336), this solution integrates LLM reasoning, automated workflow execution, and extensible plugin support for quiz formats.

📌 Description

TDS LLM Quiz Solver is a modular, Python-first autonomous agent that leverages large language models (LLMs) to interpret, reason, and solve quiz questions with minimal human intervention. This project provides clear APIs, environment configuration, and execution scripts for producing high-accuracy quiz solutions in an automated pipeline.

🧰 Tech Stack

Python 3.10+ — core application and logic

LLM Integration — OpenAI API (GPT family)

Docker — containerized runtime environment

GitHub Actions — (optional) CI/CD

Requirements Management — requirements.txt

⭐ Features

✔ Autonomous LLM-based quiz interpretation
✔ Modular agent pipeline for extensibility
✔ Configurable prompts & chain logic
✔ CLI execution & script usage
✔ Dockerized runtime for consistency
✔ MIT licensed

⚙ Installation

Follow these steps to get set up locally:

Clone the repository

git clone https://github.com/23f2004336/tds_p2_llm_quiz_solver.git
cd tds_p2_llm_quiz_solver


Create a Python virtual environment

python3 -m venv venv
source venv/bin/activate


Install dependencies

pip install --upgrade pip
pip install -r requirements.txt


Configure environment variables
Create a .env file and add your API keys (e.g., OpenAI key):

OPENAI_API_KEY=your_api_key_here

▶ How to Run
🐍 Direct Python
python main.py

🧠 Use CLI
python run_quiz_solver.py --input quiz_questions.json

🐳 Docker (optional)

Build image

docker build -t tds_quiz_solver .


Run container

docker run --env-file .env tds_quiz_solver


Replace quiz_questions.json with your quiz input payload.

🗂 Folder Structure
tds_p2_llm_quiz_solver/
├── README.md
├── requirements.txt
├── .env.example
├── main.py
├── run_quiz_solver.py
├── solver/
│   ├── __init__.py
│   ├── agent.py
│   ├── prompt_manager.py
│   ├── llm_adapter.py
├── utils/
│   ├── config.py
│   ├── logger.py
├── tests/
│   ├── test_llm_adapter.py
│   └── test_agent.py
├── Dockerfile
└── LICENSE
