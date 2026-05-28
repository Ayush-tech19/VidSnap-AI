🎬 VidSnapAI – AI Powered Reel Generator
An AI-powered web application that transforms simple images and text into engaging reel-style videos automatically using Flask, FFmpeg, and ElevenLabs AI Voice API 🚀
This project allows users to upload multiple images, enter a script or caption, and generate a complete vertical reel with realistic AI-generated voice narration.

✨ Features
📤 Upload multiple images
🧠 Convert text into realistic AI voice
🎬 Automatically generate vertical reels
⚡ FFmpeg-based video processing
🖼️ Dynamic reel gallery page
🔄 Automated reel generation pipeline
📁 Unique folder creation using UUID
🌐 Clean Flask web interface

🛠️ Tech Stack
Technology     Usage
Python 🐍     Core backend logic
Flask          Web framework
HTML/CSS       Frontend UI
FFmpeg         vedio genration
ElevenLabs API  AI voice generation


📂 Project Structure
VidSnapAI/
│
├── static/
│   ├── reels/              # Generated reels
│   └── songs/              # Images & assets
│
├── templates/
│   ├── base.html
│   ├── create.html
│   ├── gallery.html
│   └── index.html
│
├── user_uploads/           # User uploaded files
│
├── config.py               # API configuration
├── main.py                 # Flask backend
├── text_to_audio.py        # AI voice generation
├── generate_process.py     # Reel generation pipeline
├── ffmpeg_command.txt
└── done.txt

⚙️ Working Flow
1️⃣ Upload Images & Text
Users upload multiple images and enter text/script through the Flask frontend interface.
2️⃣ Backend File Handling (main.py)
This file handles:
Flask routing
Multiple file uploads
UUID-based folder creation
Saving images and text data
Managing user input
3️⃣ AI Voice Generation (text_to_audio.py)
This module:
Connects with the ElevenLabs API
Converts user text into realistic AI speech
Applies custom voice settings
Saves generated audio as .mp3
4️⃣ Reel Generation (generate_process.py)
This script continuously:
Monitors uploaded folders
Reads image/audio data
Executes FFmpeg commands
Combines images + audio
Generates vertical reel videos automatically
5️⃣ Gallery Display
Generated reels are dynamically displayed inside the gallery page using Flask templates
