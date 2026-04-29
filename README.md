#  AI Customer Support Chat Assistant

##  Summary
This project is an AI-powered customer support assistant that allows users to chat directly with an AI system. It understands user queries, detects intent and urgency, and generates helpful responses. The system also supports multilingual replies (English and Arabic) and maintains conversation context.

---

## Features
- Intent detection (refund, complaint, query, unknown)
- Urgency classification (low, medium, high)
- Context-aware reply generation (not generic)
- Multi-turn conversation (chat memory)
- English + Arabic responses (user-controlled)
- Structured JSON output for backend use
- Chat-style UI for real-time interaction
- Fallback handling for edge cases
- Animated typing indicator for better UX
- Chat-style UI for real-time interaction

---

##  Tech Stack
- Python (FastAPI)
- OpenRouter API (LLM)
- HTML + JavaScript (Frontend)

---

## How it works
- The frontend sends user queries to a FastAPI backend.
- The backend calls an AI model via OpenRouter API.
- The model processes the query and returns structured responses, which are displayed in the chat UI.

##  Setup Instructions

### 1. Install dependencies

pip install -r requirements.txt

### run the server

uvicorn app:app --reload

### open the UI
http://127.0.0.1:8000/ui
