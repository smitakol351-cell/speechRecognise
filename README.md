🧑‍💻 Voice Assistant 

This is a simple Python-based Voice Assistant that works like a personal AI .
It can recognize your voice, process commands, speak responses, and perform a variety of tasks such as searching Wikipedia, opening applications, playing YouTube videos, and browsing the internet.

🚀 Features

🎙️ Voice Recognition – Listens and understands spoken commands using speech_recognition.

🔊 Text-to-Speech (TTS) – Responds with a natural voice using pyttsx3.

📖 Wikipedia Search – Provides quick summaries from Wikipedia.

🌐 Web Automation – Opens websites like YouTube, Google, GitHub, etc.

▶️ YouTube Control – Plays/searches videos on YouTube directly by voice.

🖥️ App Launcher – Opens applications like Notepad, Calculator, Excel, Word, and more (customizable).

⏰ Time Updates – Tells the current system time.

💬 Basic Conversation – Responds to greetings and small talk.

🛠️ Requirements

Install dependencies before running the project:

pip install wikipedia
pip install pyaudio
pip install pyttsx3
pip install SpeechRecognition

📂 How It Works

The assistant greets you according to the time of day.

It listens continuously for your commands.

Based on keywords in your speech, it performs actions like:

"Open YouTube" → Opens YouTube in browser.

"Search Wikipedia Albert Einstein" → Reads a short summary from Wikipedia.

"Play lo-fi music on YouTube" → Searches and plays music.

"Open Notepad" → Launches applications from your system.

"What time is it" → Tells the current time.

You can exit anytime by saying "Exit".

📸 Example Commands

"Wikipedia Python programming"

"Open Google"

"Open GitHub"

"Play motivational songs on YouTube"

"Open Calculator"

"What time is it"

🔧 Customization

Modify app_paths in open_application() to add your own software.

Adjust voice, speech rate, and volume using the pyttsx3 engine settings.

Add more websites or commands inside the main loop for new features.

🎯 Future Enhancements

Add chatGPT integration for smarter conversations.

Include weather updates and news headlines.

Add email/SMS automation.

Make it cross-platform (Windows/Linux/Mac).

🏆 Credits

Developed in Python using:

speech_recognition

pyttsx3

wikipedia

webbrowser

datetime

os
