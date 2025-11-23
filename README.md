# AI Notes Generator

Convert classroom audio or uploaded notes into clean, summarized study notes, bullet lists, quiz questions, and diagrams.

## Features
- Audio transcription (Whisper or other STT)
- Automatic summarization (LLM)
- Bullet point extraction and highlights
- Generate quiz questions
- Simple web UI for upload and results

## Tech stack
- Backend: Python (FastAPI)
- Transcription: Whisper / OpenAI audio endpoints
- Summarization: LLM (Gemini/ChatGPT/local)
- Storage: S3 or local filesystem

## Quickstart
1. `git clone <repo>`
2. `python -m venv venv && source venv/bin/activate`
3. `pip install -r requirements.txt`
4. `uvicorn app:app --reload`
