🎬 VidSnapAI (AI Reel Generator)
An AI-powered Flask application that generates reel-style videos from images and text using FFmpeg and ElevenLabs API.
🚀 Features
Upload multiple images
Generate AI voice from text
Automatic reel generation
FFmpeg video processing
Dynamic gallery page
Flask-based web interface
🛠️ Requirements
Python 3.x
Flask
FFmpeg
ElevenLabs API
Requests library
Install dependencies:
Bash
pip install -r requirements.txt
📂 Project Structure
Bash
main.py
text_to_audio.py
generate_process.py
templates/
static/
config.py
⚙️ How to Use
1. Clone Repository
Bash
git clone https://github.com/your-username/VidSnapAI.git
cd VidSnapAI
2. Add API Key
Inside config.py
Python
ELEVENLABS_API_KEY = "YOUR_API_KEY"
3. Run Flask App
Bash
python main.py
4. Start Reel Generation Process
Bash
python generate_process.py
