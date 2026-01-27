🤖 LLM Quiz Solver – TDS Project 2

Tools in Data Science | IIT Madras BS (Diploma in Data Science)

An intelligent Python-based application that uses a Large Language Model (LLM) to automatically solve quiz-style questions.
This project was developed as part of Tools in Data Science (TDS) course in the IIT Madras BS in Data Science program.

📌 Project Overview

The LLM Quiz Solver is designed to:

Read and understand quiz questions

Use an LLM for reasoning and answer generation

Produce structured outputs automatically

Run as a standalone script or inside Docker

This project demonstrates practical usage of:

API-based AI models

Python automation

Modular project design

Environment-based configuration

🧠 Tech Stack

Python 3.10+

Large Language Model (OpenAI API)

Docker

Environment Variables (.env)

GitHub

✨ Features

✅ Automatically solves quiz questions
✅ Uses LLM for reasoning and response generation
✅ Modular and clean code structure
✅ Supports environment-based configuration
✅ Dockerized for portability
✅ Easy to extend for other question formats

⚙ Installation

1️⃣ Clone the repository
git clone https://github.com/23f2004336/tds_p2_llm_quiz_solver.git
cd tds_p2_llm_quiz_solver

2️⃣ Create virtual environment
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate

3️⃣ Install dependencies
pip install -r requirements.txt

4️⃣ Setup environment variables
Create a .env file:
OPENAI_API_KEY=your_api_key_here

▶ How to Run
Run using Python
python main.py
Run using Docker
docker build -t tds-llm-solver .
docker run --env-file .env tds-llm-solver

🗂 Folder Structure
p2/
│
├── hybrid_tools/          # Utility and helper modules
│
├── api_key_rotator.py     # Handles API key rotation for LLM requests
├── hybrid_agent.py        # Core LLM agent logic
├── hybrid_main.py         # Main entry point of the application
├── remote_logger.py       # Remote logging functionality
│
├── pyproject.toml         # Project configuration and dependencies
├── Dockerfile             # Docker configuration for containerized execution
└── README.md              # Project documentation


🎓 Academic Context

This project was completed as part of:

Tools in Data Science (TDS)
Diploma in Data Science
IIT Madras BS Degree Programme

It focuses on applying:

APIs

Automation

Software engineering practices

AI-assisted problem solving
