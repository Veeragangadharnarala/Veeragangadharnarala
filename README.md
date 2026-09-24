# MoodWave

Mood-aware music recommendation prototype built with React/Vite and FastAPI.

Features: mood selection, energy slider, recommendation API, responsive UI, and local/licensed audio playback. This is an independent prototype and does not clone Spotify or access private Spotify systems.

## Run backend
```bash
cd backend
python -m venv .venv
# Windows: .venv\Scripts\activate
# macOS/Linux: source .venv/bin/activate
pip install -r requirements.txt
uvicorn app.main:app --reload --port 8000
```

## Run frontend
```bash
cd frontend
npm install
npm run dev
```

Portfolio description: Built MoodWave, a mood-aware music recommendation prototype using React, FastAPI, and Python. Designed a recommendation engine that maps mood and energy preferences to song metadata and implemented a responsive music-player interface for local or licensed audio assets.
