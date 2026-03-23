# Health Assistant Agent

Health Assistant Agent is an AI-powered tool to help individuals manage medications and daily health routines. It provides personalized support for tracking adherence, logging symptoms, and generating insights, all while prioritizing user privacy.

## Key Features
- **Medication Reminders**: Schedule and receive timely alerts for medication doses.
- **Symptom Logging**: Record and track symptoms over time with easy input.
- **Adherence Tracking**: Monitor consistency with visual progress reports.
- **Quick Insights**: Get AI-generated summaries and health pattern observations.

## Tech Stack
- Python, FastAPI
- PostgreSQL
- React (frontend)
- OpenAI API / LLM integration

## Getting Started
1. Clone the repository: `git clone https://github.com/zoreanuj/health-assistant-agent.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Set up environment variables (see `.env.example`).
4. Run the backend: `uvicorn main:app --reload`