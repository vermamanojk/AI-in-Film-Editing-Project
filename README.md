# AI-in-Film-Editing-Project
🎬 AI-Powered Automated Film Editor
This project is an automated video editing pipeline designed to handle the tedious parts of film production—like transcribing audio, syncing subtitles, and applying transitions—using Artificial Intelligence.

🚀 Overview
Built with Python, OpenAI Whisper, and MoviePy, this tool takes raw video clips and transforms them into a polished video with a thematic title, smooth cinematic transitions, and perfectly aligned subtitles.

✨ Key Features

AI Transcription: Leverages the Whisper 'base' model to generate precise, timestamped text segments from your audio.

Contextual Titling: The system analyzes the transcript to programmatically suggest a creative title for the film.
Smooth Transitions: Implements "negative padding" logic to ensure CrossFades and Slides overlap correctly for a professional look.
Dynamic Subtitling: Subtitles are automatically wrapped and positioned to avoid being cut off at the screen edges.
Interactive UI: A dedicated Streamlit dashboard for easy file uploads and real-time rendering progress.

🛠️ Tech Stack
Frontend: Streamlit

AI Engine: OpenAI Whisper (Transformer-based ASR)

Video Processing: MoviePy (v2.0+)

Progress Tracking: Proglog

📥 Installation & Usage
Clone the Repo:

Bash

git clone https://github.com/yourusername/ai-film-editing.git
cd ai-film-editing
Install Dependencies:

Bash

pip install streamlit openai-whisper moviepy proglog
Install ImageMagick: (Required by MoviePy for text rendering. Download from ImageMagick.org)

Run the Studio:

Bash

streamlit run ai_film_editor.py
🧠 AI Usage Disclosure
This project utilizes the OpenAI Whisper model for speech-to-text inference. Large Language Models (LLMs) were used during development to assist with debugging complex rendering issues and structuring technical documentation.

Developed as part of the Module E: AI Applications project track.
