# Starter Issues for AI Notes Generator

## Good First Issue — Add sample audio + transcript
- Add `sample_data/class1_audio.mp3` and its transcript in `sample_data/transcripts.csv`.
- Labels: `good first issue`, `data`

## Help Wanted — Implement summarization endpoint
- Create `/summarize` endpoint that accepts text and returns condensed bullets using an LLM (or simple extractive algorithm)
- Labels: `help wanted`, `backend`, `ml`

## Bug — Transcription fails for long audio (>15 mins)
- Add chunking and retry logic in transcription pipeline.
- Labels: `bug`, `audio`
