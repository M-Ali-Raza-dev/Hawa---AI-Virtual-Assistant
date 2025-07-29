Hawa - AI Virtual Assistant
Hawa is a multilingual AI virtual assistant with voice recognition capabilities, developed in Python. It supports both English and Urdu languages, offering a range of features from web browsing to schedule management.

Features ✨
Dual Language Support: Works in both English and Urdu

Voice Recognition: Authenticate and control using voice commands

Smart Assistant Capabilities:

Open websites (YouTube, Google, WhatsApp, etc.)

Play music and videos

Tell jokes and current time/day

Manage your daily schedule

Send emails through voice commands

Launch applications (VS Code, MS Office, etc.)

Beautiful GUI: Customtkinter-based modern interface

Voice Lock System: Secure access with voice password

Installation 🛠️
Clone the repository:

bash
git clone https://github.com/yourusername/hawa-ai-assistant.git
cd hawa-ai-assistant
Install required dependencies:

bash
pip install -r requirements.txt
Run the application:

bash
python ai.py
Requirements 📋
Python 3.7+

Required packages:

text
customtkinter
pyttsx3
SpeechRecognition
Pillow
pyjokes
googletrans==4.0.0-rc1
gTTS
Usage 🎤
Select your preferred language (English/Urdu)

Choose authentication method:

Voice unlock (say "Salam")

Manual login (username: 123, password: 123)

Interact with Hawa using voice commands

Sample Commands 🗣️
English:

"Open YouTube"

"What's the time?"

"Tell me today's schedule"

"Send email"

Urdu:

"YouTube kholo"

"Time batao"

"Aaj ka schedule batao"

"Email bhejo"

Project Structure 📂
text
hawa-ai-assistant/
├── ai.py                # Main application file
├── images/              # GUI assets
│   ├── background1.png
│   ├── btn.png
│   ├── hyy (2).png
│   ├── password_icon.png
│   ├── show.png
│   ├── hide.png
│   ├── siri2.png
│   └── username_icon.png
├── requirements.txt     # Dependency list
└── README.md            # This file
Contributing 🤝
Contributions are welcome! Please fork the repository and create a pull request with your improvements.
