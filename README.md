🎬 VidSnapAI
An AI-powered Reel Generator built using Python, Flask, FFmpeg, and ElevenLabs API 🚀
This project allows users to upload images, enter text, and automatically generate reel-style videos with realistic AI-generated voice narration.
✨ Features
Upload multiple images
Generate AI voice from text
Automatic reel generation
FFmpeg video processing
Dynamic gallery page
Flask-based web interface
🛠️ Tech Stack
Python
Flask
HTML/CSS
FFmpeg
ElevenLabs API
📂 Project Workflow
🔹 main.py
Handles Flask routes, file uploads, UUID folder creation, and user input storage.
🔹 text_to_audio.py
Converts user text into AI-generated speech using the ElevenLabs API.
🔹 generate_process.py
Processes uploaded files and generates reels automatically using FFmpeg.
🔹 templates/
Contains frontend HTML templates for the UI and gallery pages.
🚀 Installation
Clone the repository:
Bash
git clone https://github.com/your-username/VidSnapAI.git
cd VidSnapAI
Install dependencies:
Bash
pip install -r requirements.txt
Add your ElevenLabs API key inside config.py
Python
ELEVENLABS_API_KEY = "YOUR_API_KEY"
Run the Flask app:
Bash
python main.py
Start the reel generation process:
Bash
python generate_process.py
📚 Learning Outcomes
Flask backend development
API integration
File handling in Python
FFmpeg automation
AI voice generation
👨‍💻 Author
Ayush 🚀
