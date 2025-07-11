
# 🎵 AI-Powered Music Memory Project

This project uses machine learning, speech-to-text, and API automation to bring back the musical memories of a loved one through modern tools.

## 📌 Overview

- Processed **13 hours of personal music recordings** (cassette digitized MP3s)
- Transcribed the audio using OpenAI's **Whisper** model
- Extracted potential song lyrics and searched for song titles using **Google Search**
- Created a **Spotify Developer App** to generate an automatic playlist
- Built a **prediction model** to suggest new songs based on listening patterns

## 🛠️ Tools & Technologies

- Python
- [OpenAI Whisper](https://github.com/openai/whisper)
- [Spotipy (Spotify API)](https://spotipy.readthedocs.io/)
- [pydub](https://github.com/jiaaro/pydub)
- FFmpeg
- Google Custom Search (optional)

## 📂 Project Structure

```
├── transcription/
│   ├── cinta_1_pista_1.mp3
│   ├── cinta_1_pista_1_transcription.txt
│   └── extracted_songs.txt
├── search/
│   └── lyrics_google_search.py
├── playlist/
│   └── spotify_playlist_creator.py
├── README.md
```

## 🚀 Getting Started

1. Clone the repo
2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Add your Spotify Developer credentials
4. Run each stage: transcription → lyrics matching → playlist creation

## 🔐 Notes

- This project uses personal family audio and is shared here as a demo of AI + ML capabilities for memory and culture preservation.
